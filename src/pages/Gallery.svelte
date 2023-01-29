<script>
    import ServerBanner from "../assets/server-banner.png";
    import ServerSpawnNight from "../assets/server-spawn-night.png";
    import ServerCustomVillage from "../assets/server-custom-village.png";
    import ServerSkyIsland from "../assets/server-sky-island.png";
    import ServerVolcano from "../assets/server-volcano.png";
    import ServerBotw2 from "../assets/server-botw2.png";

    const imgData = [
        { "id": 1, "params": { "src": ServerBanner, "alt": "SlimeCraftSMP Spawn" } },
        { "id": 2, "params": { "src": ServerSpawnNight, "alt": "SlimeCraftSMP Spawn at Night" } },
        { "id": 3, "params": { "src": ServerCustomVillage, "alt": "SlimeCraftSMP Custom Village" } },
        { "id": 4, "params": { "src": ServerSkyIsland, "alt": "SlimeCraftSMP Sky Island" } },
        { "id": 5, "params": { "src": ServerVolcano, "alt": "SlimeCraftSMP Volcano" } },
        { "id": 6, "params": { "src": ServerBotw2, "alt": "SlimeCraftSMP Best of the Week 2" }, "caption": "Submission by ReaperRolys" }
        ];
</script>

<main>
    {#each imgData as data (data.id)}
        {#if data.caption}
            <p>{data.caption}</p>
        {/if}

        <img { ...data.params } />
    {/each}
</main>

<style>
    main {
        display: flex;
        flex-direction: column-reverse;
        align-items: center;
    }
    img {
        aspect-ratio: initial;
        width: 45rem;
        margin-top: 64px;
    }
    img:first-of-type {
        margin-bottom: 64px;
    }
    p {
        color: #7777ff;
        text-shadow: 0 0 4px rgba(119, 119, 255, 170);
        text-align: center;
        font-size: 0.9em;
    }
</style>
