<script>
    import Back from "$lib/Back.svelte";
    import Forward from "$lib/Forward.svelte";
</script>

<section>
    <a href="/i-love-web"><Back/></a>
    <h1>reading material</h1>
    
    <article>
        <ul>
            <li><a href="https://ishadeed.com/article/modern-css-feature-image/" target="_blank">Modern CSS Feature Image</a></li>
            <li><a href="https://css-tricks.com/knowing-css-is-mastery-to-frontend-development/" target="_blank">CSS Meesterschap in Frontend Development</a></li>
            <li><a href="https://ishadeed.com/article/css-has-guide/" target="_blank">CSS :has() Gids</a></li>
            <li><a href="https://htmhell.dev/adventcalendar/2024/7/" target="_blank">HTMHell Adventskalender 2024</a></li>
            <li><a href="https://www.bram.us/2023/10/23/css-scroll-detection/" target="_blank">CSS Scroll Detectie</a></li>
            <li><a href="https://infrequently.org/2024/11/if-not-react-then-what/" target="_blank">If Not React, Then What?</a></li>
            <li><a href="https://wattenberger.com/thoughts/llms-as-a-tool-for-thought" target="_blank">LLMs als Denktool</a></li>
            <li><a href="https://everythingchanges.us/blog/stay-in-the-gap/" target="_blank">Blijf in de Tussenruimte</a></li>
            <li><a href="https://www.erikkroes.nl/blog/dont-test-accessibility-with-a-screen-reader/" target="_blank">Test Toegankelijkheid Niet Alleen met een Screenreader</a></li>
            <li><a href="https://developer.chrome.com/docs/devtools/coverage/?utm_source=lighthouse&utm_medium=devtools" target="_blank">Chrome DevTools Coverage Gids</a></li>
            <li><a href="https://londonwebstandards.org/talks/everything-you-need-to-know-about-invoker-commands/" target="_blank">Alles over Invoker Commands</a></li>
            <li><a href="https://frontendmasters.com/blog/three-approaches-to-the-ampersand-selector-in-css/?utm_source=CSS-Weekly&utm_campaign=Issue-606&utm_medium=web" target="_blank">Drie Benaderingen voor de Ampersand Selector in CSS</a></li>
            <li><a href="https://martijnhols.nl/blog/accessibility-essentials-every-front-end-developer-should-know" target="_blank">Toegankelijkheidsessentials voor Frontend Developers</a></li>
          </ul>
    </article>
</section>
<style>
    h1 {
        -webkit-text-stroke: 1px var(--basic-white);
        color: var(--rose-pompadour);
    }

    a {
        color: var(--cherry-blossom-pink);
    }
</style>