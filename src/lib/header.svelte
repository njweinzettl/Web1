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

<div class='test'>
    <h1>Welcome to the <span class="highlight">{words}</span> ever!</h1>
</div>