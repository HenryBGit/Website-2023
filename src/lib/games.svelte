<section class="grid">
    <!--Text pops up on the images-->
    
        <img class="grid-items" src="/Images/Oxenfree banner.jpg" alt="Oxenfree"/> <!--Oxenfree banner--> 
        <h1>Oxenfree</h1>
        <img class="grid-items" src="/Images/oxenfree banner 2.jpeg" alt="Oxenfree 2"/> <!--Oxenfree 2 banner-->
        <h1>Oxenfree 2</h1> 
        <img class="grid-items" src="/Images/Afterparty banner.jpg" alt="Afterparty"/> <!--AfterParty banner--> 
        <h1>Afterparty</h1>
        <img class="grid-items" src="/Images/next stop nowhere banner.jpg" alt="Next Stop Nowehere"/> <!--Next Stop Nowhere Banner-->
        <h1>Next Stop Nowhere</h1>
        <img class="grid-items" src="/Images/Mr robot banner.jpg" alt="Mr Robot"/> <!--Mr Robot banner--> 
        <h1>Mr Robot</h1>
     
</section>

<style>
    
    .grid {
        display: grid;
        align-items: center;
        width: 50vw;
        margin: auto;
    }
    .grid-items {
        grid-template-rows: 1fr 1fr;
        display: flex;
        justify-content: center;
        width:100%;
        transition: 0.125s ease-in;
    }
    .grid-items:hover {
        cursor: pointer;
        transform: scale(0.95);
    }
    h1 {
        display: flex;
        justify-content: center;
        font-family: 'DM Sans', sans-serif;
    }

</style>