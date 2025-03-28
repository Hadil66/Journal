<script>
    import Back from "$lib/Back.svelte";
    import Forward from "$lib/Forward.svelte";
</script>

<section>
    <a href="/i-love-web"><Back/></a>
    <h1>morning munch & watch</h1>
   
    <article>
        <iframe width="909" height="511" src="https://www.youtube.com/embed/oXSFwix7eR8" title="Modern CSS for sites: View transitions, scroll effects, and more!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <iframe width="909" height="511" src="https://www.youtube.com/embed/SDI8ubVZi7w" title="Config 2024: In defense of an old pixel (Marcin Wichary, Director of Design, Figma) | Figma" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <iframe width="909" height="511" src="https://www.youtube.com/embed/aYyZUDFZTrM" title="JavaScript framework reinvents itself… Did &quot;runes&quot; just ruin Svelte?" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </article>
</section>

<style>
    h1 {
        -webkit-text-stroke: 1px var(--basic-white);
        color: var(--rose-pompadour);
    }

    iframe {
        width: 350px;
        height: 250px;
    }

    a {
        color: var(--cherry-blossom-pink);
    }
</style>