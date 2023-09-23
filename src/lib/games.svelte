<section class="grid">
    <!--Text pops up on the images-->
    <img class="grid-items" src="/Images/Oxenfree banner.jpg" alt="Oxenfree"/> <!--Oxenfree banner-->
    <img class ="grid-items" src="/Images/oxenfree banner 2.jpeg" alt="Oxenfree 2"/> <!--Oxenfree 2 banner-->
    <img class="grid-items" src="/Images/Afterparty banner.jpg" alt="Afterparty"/> <!--AfterParty banner-->
    <img class="grid-items" src="/Images/next stop nowhere banner.jpg"  alt="Next Stop Nowehere"/>
    <img class="grid-items" src="/Images/Mr robot banner.jpg" alt="Mr Robot"/> <!--Mr Robot banner-->
    <div class="text"> 
        <h2 class="hide">Oxenfree</h2>
        <h2 class="hide">Oxenfree Ⅱ</h2>
        <h2 class="hide">AfterParty</h2>
        <h2 class="hide">Next Stop Nowhere</h2>
        <h2 class="hide">Mr Robot</h2>
    </div>
   
</section>
<style>
    .grid {
        display: grid;
        grid-gap: 100px;
        align-items: center;
        width: 76vw;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 1fr 1fr 1fr;
        margin: auto;
        padding-top: 10%;
        padding-bottom: 4%;
    }
    .grid-items {
        display: flex;
        justify-content: center;
        width:100%;
        transition: 0.125s ease-in;
    }
    .grid-items:hover {
        cursor: pointer;
        transform: scale(0.95);
       /* Need to make it so this transitions slowly instead */
    }
    .text {
        font-family: 'DM Serif Display', serif;

    }
    /* .hide {
        display: none;
    } */
    /* .hide:hover {
        display: flex;
    } */
</style>