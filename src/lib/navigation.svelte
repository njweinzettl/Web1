<nav>
    <ul>
        <li>Home</li>
        <li>About</li>
        <li>Contact Me</li>
    </ul>
</nav>

<!-- NAV bar styling -->

<style>
    nav{
        position: fixed;
        top:0;
        left: 0;
        right: 0;
        color: white;
        display: flex;
        justify-content: center;
        width: 100%;
        background: #111;
    }

    nav ul{
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        max-width: var(--max-width);
    }

    nav ul li{
        padding: 20px;
        display: flex;
    }

    nav ul li:last-of-type{
        margin-left: 500px;
    }

</style>