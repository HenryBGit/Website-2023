<script>
import {videoData} from "./videos.js";
let videos = videoData;
</script>
<section class="grid">
    {#each videos as video}
            <a href="{video.link}">{video.name}</a>
    {/each}
</section>