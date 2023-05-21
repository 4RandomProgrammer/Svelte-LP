<script>
  import "../app.css";
  import "@fontsource/montserrat/700.css";
  import "@fontsource/montserrat/600.css";
  import "@fontsource/montserrat/400.css";
  import "@fontsource/mulish";
    import Navbar from "../lib/components/Navbar.svelte";
</script>

<div class="w-full min-h-screen">
    <Navbar />
    <slot />
</div>

<style lang="postcss" global>
    :global(button){
        @apply px-6 py-3 font-sans rounded-full outline-none;
    }
    :global(button.primary) {
        @apply bg-primary text-white;
    }

    :global(button.outline) {
        @apply border-white text-white border-[1px];
    }

    button.outline-black{
        @apply border-black text-black border-[1px];
    }

</style>