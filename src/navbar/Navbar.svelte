<script>
    import NavItem from './NavItem.svelte';
    let items = ['browse', 'home', 'account']
</script>

<style>
    div {
        display: flex;
        flex-direction: row;
        justify-content:space-around;
        align-items: center;
    }
</style>

<div>
    {#each items as item}
        <NavItem title={item} />
    {/each}
</div>
