<script>
    import { each } from "svelte/internal";
    const images = [
        {title:'Showcase-1', src:'/images/showcase-1.png'},
        {title:'Showcase-2', src:'/images/showcase-2.png'},
        {title:'Showcase-3', src:'/images/showcase-3.png'},
        {title:'Showcase-4', src:'/images/showcase-4.png'},
        {title:'Showcase-5', src:'/images/showcase-5.png'},
        {title:'Showcase-6', src:'/images/showcase-6.png'},
        {title:'Showcase-7', src:'/images/showcase-7.png'},
        {title:'Showcase-8', src:'/images/showcase-8.png'}
    ]
        
    
</script>

<ul>
    {#each images as {title,src}}
    <li>
        <img src={src} alt={title}/>
    </li>
    {/each}
</ul>