<script>
  import { onMount } from "svelte";
  import { Navbar } from "./navbar/Navbar"
  let pages = ['browse', 'portfolio', 'account']
  export let date;

  onMount(async () => {
    const res = await fetch("/api/date");
    const newDate = await res.text();
    date = newDate;
  });
</script>

<main>
  <h1>Svelte + Node.js API</h1>
  <Navbar></Navbar>
</main>
