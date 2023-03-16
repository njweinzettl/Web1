<!-- we put the nav into a component because you write it once and can use it in several places -->

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
        top: 120px;
        left: 40px;
        right: 0;
        color: white;
        display: flex;
        justify-content: left;
        width: 100%;
    }

    nav ul{
        list-style: none;
        margin: 0;
        padding: 0;
        max-width: var(--max-width);
        display: grid;
    }

    nav ul li{
        padding: 20px;
        display: flex;
    }
</style>