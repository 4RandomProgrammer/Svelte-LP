<script>
    import { each } from "svelte/internal";
    export let images;
    
</script>

<ul class="flex overflow-hidden space-x-8">
    {#each images as {title,src}}
    <li class="shrink-0 snap-center">
        <img src={src} alt={title} class="w-[360px] h-[201px]"/>
    </li>
    {/each}
</ul>