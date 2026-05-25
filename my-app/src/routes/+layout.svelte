<svelte:head>
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Gothic+A1&display=swap" rel="stylesheet">
</svelte:head>
<script>
    import "./styles.css";
</script>
<div class="container nav">
    <nav>
        <a href="/" class="nav-text">Home</a>
        <a href="/about" class="nav-text">About</a>
        <a href="/projects" class="nav-text projects">Projects</a>
    </nav>
</div>

<slot />

<div class="container footer">
    <footer>
        <div class="subcontainer footer-container">
            <div>Contact me at <a href="mailto:dcondroski@gmail.com">dcondroski@gmail.com</a></div>
            ·
            <div>Connect on <a href="https://www.linkedin.com/in/david-condroski-0031b722a/">LinkedIn</a></div>
        </div>
    </footer>
</div>

<style>
    #footer-svelte-logo {
        height: 1rem;
    }
</style>