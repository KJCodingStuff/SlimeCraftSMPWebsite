<script>
    import ServerBanner from "../assets/server-banner.png";
    import ServerSpawnNight from "../assets/server-spawn-night.png";
    import ServerCustomVillage from "../assets/server-custom-village.png";
    import ServerSkyIsland from "../assets/server-sky-island.png";
    import ServerVolcano from "../assets/server-volcano.png";
    import ServerBotw2 from "../assets/server-botw2.png";

    const imgData = [
        { "src": ServerBotw2, "alt": "SlimeCraftSMP Best of the Week 2", "caption": "Submission by ReaperRolys" },
        { "src": ServerVolcano, "alt": "SlimeCraftSMP Volcano" },
        { "src": ServerSkyIsland, "alt": "SlimeCraftSMP Sky Island" },
        { "src": ServerCustomVillage, "alt": "SlimeCraftSMP Custom Village" },
        { "src": ServerSpawnNight, "alt": "SlimeCraftSMP Spawn at Night" },    
        { "src": ServerBanner, "alt": "SlimeCraftSMP Spawn" }
    ];
</script>

<main>
    {#each imgData as data}
        <img { ...data } />

        {#if data.caption}
            <p>{data.caption}</p>
        {/if}
    {/each}
</main>

<style>
    main {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 64px;
    }
    img {
        aspect-ratio: initial;
        width: 45rem;
        margin-bottom: 64px;
    }
    p {
        color: #FFA500;
        text-align: center;
        font-size: 0.9em;
        margin-top: -48px;
        margin-bottom: 64px;
    }
</style>
