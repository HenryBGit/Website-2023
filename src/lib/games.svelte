<section class="grid">
    <!--Need to change out the videos to images and then make the images turn into a video on hover-->
    <video class="grid-items" src="/Videos/ox-video-bg_compress_opt.mp4" loop /> <!--Oxenfree video-->
    <video class="grid-items" src="/Videos/lighthouse_1_opt.mp4" loop />  <!--Oxenfree 2 video-->
    <video class="grid-items" src="/Videos/Afterparty_loop_compress_opt.mp4" loop />  <!--AfterParty video-->
    <video class="grid-items" src="/Videos/route3-shorterclip_opt.mp4" loop /> <!--Next Stop Nowhere-->
    <img class="grid-items" src="/Images/Mr robot banner.jpg"/> <!--Mr Robot Banner-->
</section>
<style>
    .grid {
        display: grid;
        grid-gap: 100px;
        align-items: center;
        width: 76vw;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 1fr 1fr 1fr;
    }
    .grid-items {
        display: flex;
        justify-content: center;
        width:75%;
    }
    .grid-items:hover {
        
        cursor: pointer;
    }
</style>