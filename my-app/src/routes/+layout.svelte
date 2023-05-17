<script>
  import "../app.css";
  import "@fontsource/montserrat";
  import "@fontsource/mulish";
    import Navbar from "../lib/components/Navbar.svelte";
</script>

<div class="w-full min-h-screen">
    <Navbar />
    <slot />
</div>

<style lang="postcss">
    :global(button){
        @apply px-6 py-3 font-sans rounded-full;
    }
    :global(button.primary) {
        @apply bg-primary;
    }
</style>