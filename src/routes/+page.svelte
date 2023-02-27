This is the root page

<!-- CSS styling -->

<style>
    
    /* make comments in CSS like this */
    
    :root{
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif ;
    }

    h1{
        color: #343234;
        font-size: 34px;
        font-weight: normal;
    }

    button{
        background-color: #a3e4ea;
        word-spacing: 3px;
        font-style: bold;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif ;
        padding: 10px;
        padding-left: 30px;
        padding-right: 30px;
        border-radius: 10px;
        outline: none;
    }

    p{
        color: #424242; 
    }

</style>


<!-- Javascript style -->

<script>
    const num = 43;
    var name = "Nadja";
    let first_name = "Nadja";

    //make comments in javascript like this
    //we will mainly use let
    let count = 0;

    //function to count the clicks on a button -> button will be created in html below
    function incrementCount()
    {
        count++ ;
    }
</script>


<!-- html -->
<!-- line 28 is same as if(count === 1) return time else return times-->

<!-- make comments in html like this-->

<h1>Welcome to SvelteKit {first_name} </h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={incrementCount}>
    Clicked {count} {count === 1? "time" : "times"}
</button>