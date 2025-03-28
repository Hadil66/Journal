<script>
    import Back from "$lib/Back.svelte";
    import Forward from "$lib/Forward.svelte";
</script>

<section>
    <a href="/"><Back/></a>
    <h1>i love web notes</h1>

    <a href="/aangeboden-materie" class="more-notes"><h2>aangeboden materie</h2> <Forward/></a>
    <a href="/zelfgevonden-materie" class="more-notes"><h2>zelfgevonden materie</h2> <Forward/></a>
    <a href="/dnf" class="more-notes"><h2>do not forget</h2> <Forward/></a>
    <a href="/reading-material" class="more-notes"><h2>reading material</h2> <Forward/></a>
    <a href="/morning-mw" class="more-notes"><h2>morning munch and watch</h2> <Forward/></a>

</section>

<style>
    h1 {
        -webkit-text-stroke: 1px var(--basic-white);
    }

    h1, h2 {
        color: var(--rose-pompadour);
    }

    .more-notes {
        display: flex;
        flex-direction: row;
        gap: 15px;
        align-items: center;
    }
</style>