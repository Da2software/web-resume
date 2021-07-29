<script>
    import { Link } from "svelte-navigator";

    let toggleMenu = false;
    function toggleClick(event) {
        toggleMenu = !toggleMenu;
    }
</script>

<main>
    <nav class="topnav {toggleMenu ? 'responsive' : ''}" id="myTopnav">
        <!-- svelte-ignore a11y-missing-attribute -->
        <a class="logo">
           <img src="/assets/img/FullLogoDa2W.png" alt="Da2sofware logo">
        </a>
        <Link to="about" class="animated fadeInLeft delay-1">About</Link>
        <Link to="/" class="animated fadeInLeft">Home</Link>
        <!-- svelte-ignore a11y-missing-attribute -->
        <a class="icon" on:click={toggleClick}>
            <i class="fa fa-bars" />
        </a>
    </nav>
</main>

