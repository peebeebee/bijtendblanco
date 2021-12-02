<header class="logo">
    <h1 class="logo__heading">
        Bijtend<br /><span>Blanco</span>
    </h1>
    <!-- <p class="logo__subheading">Webdevelopment consultancy</p> -->
</header>

<style>

    :root {
        --border-color: red;
        --heading-color: blue;
        --subheading-color: red;
    }

    .logo {
        /* border: 1px solid var(--border-color); */
        text-align: left;
        /* max-width: 240px; */
		/* margin: 0 auto; */
        padding: 20rem 3.2rem 4.6rem 3.2rem;
        /* margin: 0 3.2rem 4.8rem 3.2rem; */
        font-size: 2.15rem;
        text-rendering: geometricPrecision;
        background-color: black;
        margin-bottom: 15rem;
    }
    
    .logo__heading {
        color: var(--heading-color);
        text-transform: none;
        font-weight: 400;
		line-height: 0.86;
        margin: 0;
        color: white;
        font-weight: 500;
        transform: perspective(458px) rotateX(3deg) rotateY(32deg);
    }

    .logo__heading span {
        letter-spacing: 0.025ch;
    }

    .logo__subheading {
        color: var(--subheading-color);
    }

</style>