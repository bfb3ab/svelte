<style>
    div {
        height: 4rem;
		width: 8rem;
        background-color: white;
        color: #FF9933;
        border-left: 0.6rem solid black;
        border-right: 0.6rem solid black;
        padding: 1rem;
        background-image: linear-gradient(45deg, #FF9933 50%, transparent 50%);
        background-position: 100%;
        transition: background 300ms ease-in-out;
    }
    div:hover{
        background-position: 0;
		color: #FF9933; 
    }
</style>

<script>
    export let title;
</script>

<div>
    <p>{title}</p>
</div>