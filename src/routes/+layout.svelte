<svelte:head>
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css"
    />

    <title>SvelteKit Markdown</title>
</svelte:head>

<div class="container">
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
        </ul>
    </nav>

    <main>
        <slot />
    </main>
</div>
