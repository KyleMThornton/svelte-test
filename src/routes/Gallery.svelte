<script>
    let galleryNum = 5;
    const galleryUp = () => {
        galleryNum++
    }

    const galleryDown = () => {
        galleryNum--
    }
</script>

<div class="gallery">
    <button on:click={galleryUp}>Lets Go Up!</button>
    <span>{galleryNum}</span>
    <button on:click={galleryDown}>Lets Go Down!</button>
</div>

<style>
    .gallery {
        display: flex;
        align-items: center;
    }

    button {
        margin: 1rem;
        padding: 1rem;
    }

    span {
        font-size: 3rem;
    }
</style>