<script>
  import "../app.css";
  import "@fontsource/montserrat/700.css";
  import "@fontsource/montserrat/600.css";
  import "@fontsource/montserrat/400.css";
  import "@fontsource/mulish/400.css";
  import "@fontsource/mulish/700.css";
  import Navbar from "../lib/components/Navbar.svelte";
  import Footer from "../lib/components/Footer.svelte";
</script>

<div class="w-full min-h-screen">
    <Navbar />
    <slot />
    <Footer />
</div>

<style lang="postcss" global>
    :global(button){
        @apply px-6 py-3 font-sans rounded-full outline-none;
    }
    :global(button.primary) {
        @apply bg-primary text-white hover:bg-blue-700;
    }

    :global(button.outline) {
        @apply border-white text-white border-[1px];
    }

    button.outline-dark{
        @apply border-black text-black border-[1px] hover:bg-black hover:text-white;
    }

</style>