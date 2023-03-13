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
