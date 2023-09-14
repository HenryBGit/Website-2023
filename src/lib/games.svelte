<section class="grid">
    <!--Need to make the images on hover turn into videos-->
    <img class="grid-items" src="/Images/oxenfree banner.jpg" /> <!--Oxenfree banner-->
    <img class ="grid-items" src="/Images/oxenfree banner 2.jpeg" /> <!--Oxenfree 2 banner-->
    <img class="grid-items" src="/Images/afterparty banner.jpg" /> <!--AfterParty banner-->
    <img class="grid-items" src="/Images/next stop nowhere banner.jpg" />
    <img class="grid-items" src="/Images/Mr robot banner.jpg"/> <!--Mr Robot banner-->
    
    
    
    <!--
    <video class="grid-items" src="/Videos/ox-video-bg_compress_opt.mp4" autoplay loop muted/> Oxenfree video
    <video class="grid-items" src="/Videos/lighthouse_1_opt.mp4" autoplay loop muted/>  Oxenfree 2 video
    <video class="grid-items" src="/Videos/Afterparty_loop_compress_opt.mp4" autoplay loop muted/>  AfterParty video
    <video class="grid-items" src="/Videos/route3-shorterclip_opt.mp4" autoplay loop muted/> Next Stop Nowhere
    -->
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
    }
    .grid-items:hover {
        cursor: pointer;
    }
    img:hover {
    border: solid 15px white;
    margin: -15px;
    z-index: 50;
    }
</style>