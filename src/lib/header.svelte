<title>Nadja Weinzettl</title>

<!-- making a word change every second in a text -->
<script>
    let words = "best page";
    let wordsarray = [
        "best", "funkiest", "craziest"
    ]
    let index = 0;

    setInterval(() => {
        words = wordsarray[index%wordsarray.length];
        index ++;
    }, 1000);

</script>

<div class='word'>
    <h1>Welcome to the <span class="highlight">{words}</span> ever!</h1>
</div>


<!-- header styling-->

<style>
    .word{
    background-image: url('images/sea.jpg');
    width: 100%;
    height: 100%;
    background-size: cover;
    background-position: center;
    padding: 200px;

    display: flex;
    justify-content: center;
    }

    .word h1{
        font-size: 50px;
        color:#051625;
        justify-content: center;
    }
</style>