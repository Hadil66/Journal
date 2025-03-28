<script>
        import Back from "$lib/Back.svelte";
</script>

<section>
    <a href="/i-love-web"><Back/></a>

    <h1> zelfgevonden materie</h1>
    <article>
        <ul>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/light-dark"><p>light-dark()</p></a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/light-dark"><p>light-dark()</p></a></li>
            <li><a href="https://web.dev/articles/light-dark"><p>light-dark()</p></a></li>
            <li><p>Google fonts zijn illegaal in europa: According to GDPR, an IP address is personal information which can be used for identifying the user. Thus, Google Fonts violates GDPR by collecting and sharing personal information with third-party services without user consent.</p></li>
            <li><a href="https://www.typotheque.com/"><p>typotheque</p></a></li>
        </ul> 
    
        <img src="/assets/prefers.png">
        <img src="/assets/@container.png">
        <img src="/assets/accessibility-ext.png">

        <ul>
            <li><p>:focus-within</p></li>
            <li><p>:user-invalid</p></li>
            <li><p>indetermate</p></li>
            <li><p>ATTRIBUTE SELECTOR!!!</p></li>
            <li><a href="https://developer.chrome.com/blog/css-text-box-trim"><p>CSS text-box-trim</p></a></li>
        </ul>
            
            <p>Simpele & selector in CSS voorbeelden: A use-case for the & selector is to combine it with the :has() pseudo-class to select and style elements based on the child elements they contain. In the following example, a label is styled for when the checkbox within it is checked.</p>
            <img src="/assets/has.png">

            <p>The & selector can be used to combine class names.</p>
            <img src="/assets/image.png">

            <article>
                <h3>Cache</h3>
                <h4>Wat is cache?</h4>
                <p>Wanneer een website wordt geopend, slaat de browser een kopie van bepaalde onderdelen van de site op in de cache. Dit wordt gedaan om de laadtijd te verkorten en de gebruikerservaring te verbeteren. Als je dezelfde website later opnieuw bezoekt, kan de browser deze opgeslagen kopie (cache) gebruiken in plaats van alles opnieuw te downloaden. Hierdoor kunnen recente wijzigingen op een website soms niet direct zichtbaar zijn.</p>

                <h4>Soorten cache:</h4>
                <ol>
                    <li><strong>Browser-cache</strong>: Wanneer je een website bezoekt, slaat je browser bepaalde elementen van die site op in de cache. Dit zorgt ervoor dat de website sneller laadt bij een volgend bezoek. Soms kan het nodig zijn om de browser-cache te legen om recente wijzigingen op een website te zien.</li>
                    <li><strong>Server-cache</strong>: Een server-cache is een techniek waarbij kopieën van webcontent, zoals webpagina’s of bepaalde gegevens, tijdelijk worden opgeslagen op een server om sneller toegang te bieden bij vervolgverzoeken. Deze cache kan lokaal op de server zelf opgeslagen zijn of worden verspreid over meerdere servers in een netwerk (bijvoorbeeld via een Content Delivery Network, of CDN). Hierdoor kunnen gebruikers sneller toegang krijgen tot de inhoud van een website, omdat de server de gegevens niet telkens opnieuw hoeft te genereren. De opslag van deze gegevens is vaak tijdelijk, afhankelijk van de instellingen van de website en de server.</li>
                </ol>

                <h4>Het belang van cache</h4>
                <p>Cache is belangrijk omdat het gegevens van een site opslaat, waardoor je bij het opnieuw openen van de site niet lang hoeft te wachten totdat deze geladen is. Ook vermindert cache het dataverbruik, omdat er minder verzoeken naar de database worden gestuurd. Doordat de gegevens lokaal zijn opgeslagen, hoeft de server minder vaak dezelfde gegevens op te halen, wat de belasting van de server vermindert.</p>

                <h4>Cache clearen</h4>

                <h5>Incognitomodus</h5>
                <p>De incognitomodus is een browserfunctie waarmee je privé op het internet kunt surfen. In deze modus worden geen eerder opgeslagen gegevens zoals cookies, cache of browsergeschiedenis gebruikt. Dit betekent dat je altijd de meest recente versie van een website ziet, zonder invloed van oude gegevens. Nadat je de modus hebt gebruikt, worden je lokale browsegegevens automatisch gewist.</p>

                <h5>Client-side</h5>
                <p>Je kunt je cache eenvoudig zelf wissen. Klik met de rechtermuisknop terwijl de gewenste site openstaat en selecteer 'Inspect' in het contextmenu. Houd vervolgens de <strong>Ctrl-toets</strong> ingedrukt en klik tegelijkertijd op de <strong>refresh button</strong>. Er verschijnt een menu waarin je de optie <strong>'Empty cache and hard reload'</strong> selecteert. Hiermee wordt je cache gewist.</p>

                <p><strong>Chrome</strong>:</p>
                <p>Open eerst Google Chrome en klik op het drie-puntjes-menu <strong>⋮</strong> in de rechterbovenhoek van de browser. Ga naar <strong>Delete Browsing Data</strong>. Vink vervolgens alleen <strong>Cached images and files</strong> aan. Dit bevestig je door op <strong>Delete data</strong> te klikken.</p>

                <p><strong>Safari</strong>:</p>
                <p>Open de Safari-instellingen, klik op <strong>Advanced</strong>, en vink onderaan de pagina <strong>Show Develop menu in menu bar</strong> aan. Bovenin verschijnt dan het tabblad <strong>Develop</strong>; klik daarop. Onderin het menu vind je <strong>Empty Caches</strong>, waar je op kunt klikken.</p>

                <p><strong>Firefox</strong>:</p>
                <p>Klik op de drie balkjes rechtsboven en kies <strong>History</strong>. Selecteer <strong>Clear recent history</strong> en stel de tijdsperiode in. Vink de optie Cache aan. Klik op <strong>Clear now</strong>. Sluit en heropen Firefox om de wijzigingen toe te passen.</p>

                <p><strong>Edge</strong>:</p>
                <p>Klik rechtsboven op het drie-puntjes-menu <strong>⋮</strong> en open <strong>Settings</strong>. Klik dan op <strong>Privacy, Search, and Services</strong>. Onder het kopje <strong>Clear browsing data</strong> vind je <strong>Choose What to Clear</strong>. Als je daarop klikt, kun je <strong>Cached images and files</strong> aanvinken. Klik tot slot op <strong>Clear now</strong> om je cache te wissen.</p>

                <h5>Server-cache</h5>
                <p>Een cache-server is een server die internetinhoud en webpagina's lokaal opslaat. Het slaat vaak opgevraagde gegevens op, zodat volgende verzoeken sneller kunnen worden beantwoord dan wanneer ze steeds van de oorspronkelijke locatie moeten komen.</p>

                <p>Hier zijn verschillende manieren om de server-cache van je WordPress-site te wissen, afhankelijk van je cache-plugin:</p>

                <p><strong>Speed Optimizer</strong></p>
                <ul>
                    <li>Op SiteGround klik je op Site Tools.</li>
                    <li>Klik vervolgens in de sidebar op <strong>Speed</strong> en daarna op <strong>Caching</strong>.</li>
                    <li>Ga naar <strong>Dynamic Cache</strong> en klik op het <strong>Flush Cache</strong> icoontje onder <strong>Actions</strong> om de cache te verwijderen.</li>
                </ul>

                <p><strong>Cloudflare</strong></p>
                <p>Als je Cloudflare gebruikt, kun je de cache via hun dashboard wissen:</p>
                <ul>
                    <li>Log in op je Cloudflare-account.</li>
                    <li>Open het dashboard van je website.</li>
                    <li>Ga naar het tabblad "Caching".</li>
                    <li>Klik op "Purge Cache" en kies of je alles of alleen specifieke bestanden wilt wissen.</li>
                </ul>

                <p><strong>WP Super Cache</strong></p>
                <ul>
                    <li>Ga in je WordPress-dashboard naar Instellingen > WP Super Cache.</li>
                    <li>Klik op de knop "Cache legen".</li>
                </ul>

                <p><strong>WP Rocket</strong></p>
                <ul>
                    <li>Ga naar Instellingen > WP Rocket.</li>
                    <li>Klik op "Cache opschonen".</li>
                </ul>

                <h4>Bronnen:</h4>
                <ul>
                    <li><a href="https://www.one.com/nl/webhosting/wat-is-een-cache">One.com</a></li>
                    <li><a href="https://www.tundra.nl/vaktaal/cache/">Tundra.nl</a></li>
                    <li><a href="https://www.thisisfever.co.uk/knowledge-hub/what-is-a-browser-cache-and-why-do-i-need-to-clear-it/">Thisisfever.co.uk</a></li>
                    <li><a href="https://its.uiowa.edu/services/how-clear-cache-and-cookies-your-web-browser">University of Iowa</a></li>
                    <li><a href="https://kinsta.com/blog/wordpress-clear-cache/#what-is-caching">Kinsta</a></li>
                    <li><a href="https://www.hostinger.com/tutorials/clear-browser-cache?utm_campaign=Generic-Tutorials-DSA|NT:Se|LO:NL&utm_medium=ppc&gad_source=1&gclid=EAIaIQobChMIm_Pf0_HMiwMVpj0IBR2FNRAEEAAYASAAEgKyJfD_BwE">Hostinger</a></li>
                    <li><a href="https://www.elegantthemes.com/blog/wordpress/clear-wordpress-cache?utm_source=Blog&utm_medium=Manual+WordPress+Targets&utm_campaign=Google+Search&retargeting=off&gad_source=1&gclid=CjwKCAiA2cu9BhBhEiwAft6IxMOzGSBY76Mh3aVvh0MqKLHaXbcKgXwYGKNdABN7w21RnJc4rv31ghoC2HUQAvD_BwE#clearing-cache-plugin-data">Elegant Themes</a></li>
                </ul>
            </article>

            <article>
                <h3>Git</h3>
                <p>Git is software that is installed in your computer. Git is like a memory card for code. Every so often, you have to enter a command to save your progress locally.</p>
                <h4>Git Commands:</h4>
                <ul>
                    <li><strong>git init</strong> - Initialize project to use Git.</li>
                    <li><strong>git add .</strong> - Add all changes to be saved.</li>
                    <li><strong>git commit -m *commit message*</strong> - Save changes with a message.</li>
                    <li><strong>rm</strong> - Delete a file.</li>
                    <li><strong>git status</strong> - Check the status of changes.</li>
                    <li><strong>git log</strong> - You can see all your saved changes.</li>
                    <li><strong>git checkout (commit hash)</strong> - You can see your commit.</li>
                    <li><strong>git branch -d *branch_name*</strong> - Delete a branch.</li>
                    <li><strong>git checkout -b *branch_name*</strong> - Create a new branch.</li>
                    <li><strong>git push origin *branch_name*</strong> - Merge branches.</li>
                    <li><strong>git pull origin master</strong> - Pull changes from the master branch.</li>
                </ul>

            </article>
    </article>
</section>

<style>
     a {
        color: var(--cherry-blossom-pink);
    }
</style>