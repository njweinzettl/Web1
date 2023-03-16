<script>
	function clickButton(){
        console.log("clicked")
    }
</script>

<button on:click={clickButton}> clicked </button>

<div>
    <ul class="tags">
        <li class="oneTag"> <button id="UX" on:click={clickButton} class="button">UX Design</button>
        </li> 
        <li class="oneTag"> <button id="UX" on:click={clickButton} class="button">Web Development</button>
        </li> 
        <li class="oneTag"> <button id="UX" on:click={clickButton} class="button">User Research</button>
        </li> 
        <li class="oneTag"> <button id="UX" on:click={clickButton} class="button">Information Visualization</button>
        </li> 
    </ul>
</div>

<!-- Tags component styling -->

<style>
    .tags{
        display: flex;
        justify-content: center;
        list-style: none;
        box-sizing: border-box;
        display: flex;
        width: 100;
        font-size: 18px;
    }

    button{
        border: none;
        background-color: none;
        margin-block-start: 1em;
        padding-inline-start: 1em;
        padding-inline-end: 1em;
        padding-top: 0.5em;
        padding-bottom: 0.5em;
        border-radius: 0.5rem;
        background: #d5d5d6;
        margin: 0 7px 7px 0;
    }

    .ph2 {
        padding-left: 0.5rem;
        padding-right: 0.5rem;
        background: grey;
    }

    .link, .link:active, .link:focus, .link:hover, .link:link, .link:visited {
        transition: color .15s ease-in;
    }
</style>
