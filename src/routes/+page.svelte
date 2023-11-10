<link rel="stylesheet" type="text/css" href="\Css\main.css"> 
<script>
import Navbar from "$lib/navbar.svelte";
import Top from "$lib/top.svelte"
</script>
<main>
    <Navbar />
    <Top />
</main>
    <section class="grid">
            <img class="grid-items" src="/Images/Oxenfree banner.jpg" alt="Oxenfree"/> <!--Oxenfree banner--> 
            <img class="grid-items" src="/Images/oxenfree banner 2.jpeg" alt="Oxenfree 2"/> <!--Oxenfree 2 banner--> 
            <img class="grid-items" src="/Images/Afterparty banner.jpg" alt="Afterparty"/> <!--AfterParty banner--> 
            <img class="grid-items" src="/Images/next stop nowhere banner.jpg" alt="Next Stop Nowehere"/> <!--Next Stop Nowhere Banner-->
            <img class="grid-items" src="/Images/Mr robot banner.jpg" alt="Mr Robot"/> <!--Mr Robot banner--> 
         
    </section>

<style>
    .grid {
        padding-top: 40px;
        display: grid;
        align-items: center;
        width: 76vw;
        margin: auto;
        padding-bottom: 4%;
        grid-gap:28px;
        
    }
    .grid-items {
        display: flex;
        justify-content: center;
        width:100%;
        transition: 0.125s ease-in;
    }
    .grid-items:hover {
        transform: scale(0.95);
    }

</style>