<script>
    import Back from "$lib/Back.svelte";
</script>
<section>
    <a href="/"><Back/></a>

    <h1>we love web</h1>

    <article>
        <h2>The rise of AI-powered Voice interfaces on the web by Dave Bitter</h2>
        <ul>
            <li>7 jaar moet hij wachten voor Voice UI</li>
            <li>History of Voice recognition:
                <ul>
                    <li>Vanaf 1950 zijn de eerste pogingen gedaan</li>
                    <li>1980 was er voortgang maar niet heel bijzonder</li>
                    <li>1990 konden computers meer features beter begrijpen</li>
                    <li>2000 kwam Google met input field microphone</li>
                    <li>2010 smart assistenten (Alexa, Siri)</li>
                </ul>
            </li>
            <li>The change on how people find information: via ChatGPT of andere AI</li>
            <li>AIva-demo: go-to knowledge buddy, via add support for human hardware, 4 key points:
                <ul>
                    <li>Speech recognition</li>
                    <li>ChatGPT API</li>
                    <li>Conversation</li>
                    <li>Logical thinking</li>
                </ul>
            </li>
            <li>Text uitlaten spreken door de computer -> op CodePen: Dave Bitter -> demo van Speech Synthesis WebAPI</li>
            <li>Connecting with AI:
                <ul>
                    <li>Hoe wordt het gebruikt</li>
                    <li>The personality of AI</li>
                    <li>The select role by the user</li>
                </ul>
            </li>
            <li>Giving it some personality & feedback to the user:
                <ul>
                    <li>Via idling</li>
                    <li>Meer beweging tijdens luisteren en reageren</li>
                </ul>
            </li>
            <li>Adding AI-powered Speech Synthesis via ElevenLabs (meerdere gratis accounts nodig voor meer keuzes)</li>
            <li>Fetch all audio data -> play all audio data, of:
                <ul>
                    <li>Fetch -> play -> fetch -> play (niet geoptimaliseerd)</li>
                    <li>Laatste versie: fetch, play en fetch, play en fetch (geoptimaliseerd en sneller)</li>
                </ul>
            </li>
            <li>Performance boven alles: niets breekt de illusie meer dan hoge latency</li>
            <li>AI is slechts een datasource: de UX maakt het verschil</li>
            <li>Vergeet oudere technieken niet</li>
            <li>Project Fubu?</li>
            <li>Make cool stuff: build, don’t just discuss</li>
            <li><a href="https://techhub.iodigital.com/tags/voice">Meer info</a></li>
        </ul>
        
    </article>

    <article>
        <h2>Emiel van Betsbrugge</h2>
        <ul>
            <li>Algemene informatie:
                <ul>
                    <li>WebGL Developer bij Active Theory</li>
                    <li>8 jaar ervaring</li>
                    <li>Devine student uit Kortrijk</li>
                </ul>
            </li>
            <li>From pitch to production</li>
            <li>Pitch: Wie, wanneer, wat, hoe en voor hoeveel</li>
            <li>People: Producers, sales, design director & tech director/lead</li>
            <li>Details:
                <ul>
                    <li>Vaak optioneel en tegen een extra betaling</li>
                    <li>Intensere design phase</li>
                    <li>Concurreren tegen andere agencies maakt het uiteindelijk de moeite waard</li>
                </ul>
            </li>
            <li>Discovery: Tijdens de build tacklen we de grootste kwesties en vragen</li>
            <li>Design & Early dev: 
                <ul>
                    <li>Statement of Work (SOW) Sign-off</li>
                    <li>Estimations</li>
                    <li>Sprint planning</li>
                    <li>Scaffolding (basis setup)</li>
                </ul>
            </li>
            <li>Development: Werkproces Emiel: Quick and dirty volledige flow -> 'fix fix' en 'polish polish'</li>
            <li>Details: Langste periode, belangrijk om design te blijven volgen en eigen stijl te behouden</li>
            <li>Polish tips: Focus op quick wins en low-effort big impact</li>
            <li>QA (Quality Assuring): 
                <ul>
                    <li>Functional QA, taal QA (LQA), build accepting, laatste polish</li>
                    <li>Vaak externe partij, vooruit plannen is cruciaal</li>
                </ul>
            </li>
            <li>GO Live: Inhoud: press of a button, meestal niet direct na het einde van de build</li>
            <li>Retrospective:
                <ul>
                    <li>What should we continue doing?</li>
                    <li>What should we stop doing?</li>
                    <li>What should we start doing?</li>
                    <li>Boilerplate aanpassen?</li>
                </ul>
            </li>
            <li>Closing note: Speed/performance is important, Quality is always the end goal, Blijf experimenteren, Please make the internet fun again</li>
        </ul>
        
    </article>
</section>


<style>
        h1 {
        -webkit-text-stroke: var(--basic-white);
    }

    h1, h2 {
        text-transform: capitalize;
        color: var(--rose-pompadour);
    }

    a {
        color: var(--cherry-blossom-pink);
    }
</style>