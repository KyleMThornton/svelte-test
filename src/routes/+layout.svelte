<script>
    import Header from "./Header.svelte";
</script>

<div class="app">
    <Header />

    <main>
        <slot />
    </main>

    <footer>
        <p>And thats all folks!</p>
    </footer>
</div>

<style>
    footer {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
</style>