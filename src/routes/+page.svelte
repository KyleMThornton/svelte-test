<script>
    import Gallery from "./Gallery.svelte";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
    <h1>Welcome to my first Svelte App</h1>
    <Gallery />
</section>

<style>
    section {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
</style>