<script>
    import { onMount } from "svelte";
    const BASE_URL='https://api.unsplash.com';

    onMount(() => {
        fetch(`${BASE_URL}/search/photos?query=cats&color=white&per_page=3&client_id=KyEE3VpO4cJdX_Ti1BB3JjHB3v0QVELLqOjQMHeX6qE`)
        .then(res => res.json())
        .then (data =>  {
            data.results.forEach(result => {
                console.log(result.urls.regular)
            })  
        })
    })
    
</script>