<script>

</script>
<div class="bg-img"></div>
<h1 class="home">Learning Journal</h1>
<nav>
    <ul>
            <li>Notes
                <ul>
                    <a href="/sprint-notes">
                        <li>Sprint notes</li>
                    </a>
                    <a href="/we-love-web">
                        <li>We love web</li>
                    </a>
                </ul>
            </li>
        <a href="/i-love-web">
            <li>I love web</li>
        </a>
        <a href="/experiments">
            <li>Experiments</li>
        </a>
    </ul>
</nav>

<style>
    h1{
        animation: FadeInHeader 3s ease-in forwards;
        color: var(--cherry-blossom-pink);
        font-family: "Tangerine bold";
        font-size: 10em;
        text-align: center;
        text-justify: center;
        text-shadow: var(--cherry-blossom-pink) 1px 0 10px;
        -webkit-text-stroke: 2px var(--rose-pompadour);
        padding: 0;
    }

    h1 {
        color: var(--cherry-blossom-pink);
        font-family: "Tangerine bold";
        text-shadow: var(--cherry-blossom-pink) 1px 0 10px;
        -webkit-text-stroke: 1px var(--rose-pompadour);
    }

    @media (min-width: 900px) {
        h1 {
            font-size: 20em;
        }
    }

    @keyframes FadeInHeader {
        0% {
            opacity: 0;
        }
        100% {
            opacity: 1;
        }    
    }

    nav {
        animation: showNav 0.8s ease-in forwards;
        bottom: 1em;
        position: absolute;
        right: 1em;
    }

    @keyframes showNav {
        0% {
            bottom: -2em;
        }
        100% { 
            bottom: 1em;
        }
    }

    ul{
        display: flex;
        flex-direction: row;
        justify-content: end;
        align-items: end;}

    li {
        color: var(--cherry-blossom-pink);
        cursor: pointer;
        display: inline-block;
        font-family: "Lato";
        font-size: 1em;
        list-style-type: "";
        margin: 0;
        padding: 10px;
        position: relative;
        -webkit-text-stroke: 1px var(--rose-pompadour);
    }

    li:hover {
        text-decoration: underline;
    }

    li ul {
        display: none;
        left: 0;
        min-width: 120px;
        padding: 0;
        position: absolute;
        top: -5em;
        transition: 0.3s ease-in forwards;
    }

     /* dropdown  */
    li:hover ul {
        display: block;

    } 

    li ul li {
        display: block;
        padding: 10px;
    } 
</style>