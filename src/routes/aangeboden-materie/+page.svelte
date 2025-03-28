<script>
    import Back from "$lib/Back.svelte";
</script>

<section>
    <a href="/i-love-web"><Back/></a>

    <h1> aangeboden materie</h1>
    <article>
        <a href="The hardest working font in Manhattan"><p>Fonts</p></a>

        <p>Marcin Wichary:</p>
        <ul>
            <li><a href="https://vimeo.com/channels/fronteers12/53317253" target="_blank"><p>Vimeo: Fronteers 2012 Talk</p></a></li>
            <li><a href="https://www.youtube.com/watch?v=vUlnxjuYyzw" target="_blank"><p>I pressed ⌘B. You wouldn’t believe what happened next </p></a></li>
            <li><a href="https://www.youtube.com/watch?v=SDI8ubVZi7w" target="_blank"><p>Config 2024: In defense of an old pixel </p></a></li>
        </ul>
        

        <p>Copilot / AI and code quality research</p>
        <ul>
            <li><a href="//www.youtube.com/watch?v=Et8CqMu_e6s" target="_blank"><p>New Research On CoPilot And Code Quality</p></a></li>
            <li><a href="//www.404media.co/microsoft-study-finds-ai-makes-human-cognition-atrophied-and-unprepared-3/" target="_blank"><p>Microsoft Study Finds AI Makes Human Cognition “Atrophied and Unprepared”</p></a></li>
        </ul>
    </article>
</section>

<style>
    h1 {
        -webkit-text-stroke: 1px var(--basic-white);
    }

    h1, h2 {
        color: var(--rose-pompadour);
    }

    img {
        width: 350px;
    }

    a {
        color: var(--cherry-blossom-pink);
    }
</style>