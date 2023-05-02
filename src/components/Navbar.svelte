<script>
    import { Link } from "svelte-navigator";

    let toggleMenu = false;
    function toggleClick(event) {
        toggleMenu = !toggleMenu;
    }
</script>

<main>
    <nav class="topnav {toggleMenu ? 'responsive' : ''}" id="myTopnav">
        <div class="nav-side">
            <!-- svelte-ignore a11y-missing-attribute -->
            <a class="logo animate__animated animate__fadeIn">
                <img src="/assets/img/FullLogoDa2W.png" alt="Da2sofware logo" />
            </a>
            <a href="#skills" class="animated fadeInLeft delay-0-4s">Skills</a>
            <a href="#work-exp" class="animated fadeInLeft delay-0-4s">Work Experience</a>
            <a href="#education" class="animated fadeInLeft delay-0-3s">Education</a>
            <a href="#about-me-site" class="animated fadeInLeft delay-0-2s">About</a>
            <a href="#home" class="animated fadeInLeft">Home</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a class="icon" on:click={toggleClick}>
                <i class="fa fa-bars" />
            </a>
        </div>
    </nav>
</main>
