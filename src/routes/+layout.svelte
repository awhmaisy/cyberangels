<script>
    import Navigation from '$lib/Navigation.svelte';
    import '/app.css';
</script>

<div class="container">
    <div class="boxy">
        <Navigation />
    </div>
    <div class="grid">
        <div class="column sidebar">
            <a href="/">
                <img src="/images/ascii.webp" style="width: 200px;" alt="Description of the image">
            </a>            
            <h3>Alumni Directory</h3>
            <ul>
                <li><a href="https://remilia.org" target="_blank" style="font-style: italic;">CLICK to be saved by Maisy</a></li>
                <li><a href="https://remilia.org" target="_blank" style="font-style: italic;">CLICK to be saved by Harmony</a></li>
                <li><a href="https://throne.com/awhmaisy" target="_blank" style="font-style: italic;">CLICK to buy an angel</a></li>
                <li><a href="https://twitch.tv/awhmaisy" target="_blank" style="font-style: italic; white-space: pre;" >CLICK to watch angels</a></li>
                <li>More to come.. we're buried in paperwork for the time being &lt;3 </li>
            </ul>
            <h3>Conglomerate Associates</h3>
            <ul>
                <li><a href="https://awhmaisy.com" target="_blank" style="font-style: italic;">Maisy's Homepage</a></li>
                <li><a href="https://envymgt.be/bbyeva02" target="_blank" style="font-style: italic;">Harmony's Homepage</a></li>
                <li><a href="https://egirlcorp.netlify.app" target="_blank" style="font-style: italic;">Egirl Corp</a></li>
                <li><a href="https://hardanimeshirts.com" target="_blank" style="font-style: italic;">We love when you get hard</a></li>
            </ul>
        </div>
        <slot />
    </div>
</div>

<style>
    .sidebar {
        width: 220px;
        padding: 10px;
    }
</style>