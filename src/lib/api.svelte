<script>
    let cats =[]
    import { onMount } from "svelte";
    const BASE_URL='https://api.unsplash.com';
    const Client_ID='KyEE3VpO4cJdX_Ti1BB3JjHB3v0QVELLqOjQMHeX6qE';

    onMount(() => {
        fetch(`${BASE_URL}/search/photos?query=cats&color=white&per_page=3&client_id=${Client_ID}`)
        .then(res => res.json())
        .then (data =>  {
            cats = data.results
            })  
        })
    
</script>
<style>
    .gallery {
        grid-template-columns: repeat(3, 1fr);
        display: grid;
        gap: 30px;
    }
</style>
<div class ="gallery">
    {#each cats as cat}
    <div style="background-image:url({cat})"></div>
        
    {/each}

</div>
