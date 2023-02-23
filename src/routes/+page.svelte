<!-- CSS stzling -->

<style>
    h1{
        color: blue;
        font-size: 34px;
        font-style: italic;
        font-weight: normal;
    }
</style>

<!-- Javascript style -->
<script>
    const num = 43;
    var name = "Adon";
    let first_name = "Adon";

    let count = 0;

    function incrementCount()
    {
        count++ ;
    }
</script>

<!-- html -->
<button on:click={incrementCount}>
    Clicked {count} {count === 1? "time" : "times"}
</button>

<!-- line 28 is same as if(count === 1) return time else return times-->

<!-- make comments -->

<h1>Welcome to SvelteKit {first_name} </h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
