<svelte:head>
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
