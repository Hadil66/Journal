<script>
    import Back from "$lib/Back.svelte";
</script>

<!-- <section>  -->

    <a href="/"><Back/></a>
    <h1> soon come.tm</h1>

<!-- </section> -->

<style>
    h1 {
        animation: glitch 1s infinite;
        color: var(--rose-pompadour);
    }

    @keyframes glitch {
  0%   { transform: translate(0); }
  20%  { transform: translate(-2px, 2px); }
  40%  { transform: translate(-2px, -2px); }
  60%  { transform: translate(2px, 2px); }
  80%  { transform: translate(2px, -2px); }
  100% { transform: translate(0); }
}

</style>