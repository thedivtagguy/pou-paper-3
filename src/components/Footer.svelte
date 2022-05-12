<script>

  import wordmark from "$svg/wordmark.svg";
  export const prerender = true;

  const links = [
    { name: "contact", url: "https://thedivtagguy.com/contact" },
    { name: "twitter", url: "https://twitter.com/thedivtagguy/" },
    { name: "instagram", url: "https://www.instagram.com/thedivtagguy"},
    { name: "github", url: "https://github.com/thedivtagguy/" }
  ];

</script>

<footer class="max-w-5xl mx-auto bg-white py-4">
<section class="about py-4">
  <div class="w-[40px] mx-auto pb-4">
    <a sveltekit:prefetch  href="/" aria-label="The thedivtagguy">{@html wordmark}</a>
  </div>
  
  <p class="text-center mx-auto text-xs font-mono font-semibold  text-black  whitespace-pre-wrap">
    &lt;/&gt; with Svelte, Tailwind, Google Docs & &lt;3 in Bangalore, IN
  </p>
</section>


</footer>
