<script>
    import DiscordLogo from "../assets/discord.svg";
    export let navigateTo;

    const discordInvite = 'https://discord.gg/xFtghGVCVD';
    const wikiInvite = 'https://slimecraftsmpwiki.gitbook.io/slimecraftsmp/';

    const navItems = [
        { "id": "home", "icon": "home", "action": () => navigateTo("home") },
        { "id": "discord", "action": () => window.open(discordInvite) },
        { "id": "rules", "icon": "menu_book", "action": () => navigateTo("rules") },
        { "id": "vote", "icon": "check_box", "action": () => navigateTo("vote") },
        { "id": "staff", "icon": "manage_accounts", "action": () => navigateTo("staff") },
        { "id": "wiki", "icon": "info", "action": () => window.open(wikiInvite) },
        { "id": "support", "icon": "settings", "action": () => navigateTo("support") },
        { "id": "gallery", "icon": "photo_library", "action": () => navigateTo("gallery") }
    ];
</script>

<nav class='navbar'>
    <span></span>

    {#each navItems as { id, icon, action }}
        <span id={id} tabindex="0" on:click={action} on:keypress={action}>

            {#if icon}
                <span class="material-icons">{icon}</span>
            {:else}
                <img src={DiscordLogo} alt="Discord logo"/>
            {/if}
            
            {id}

            {#if id == "discord" || id == "wiki"}
                <span class="material-icons">open_in_new</span>
            {/if}
        </span>
    {/each}

    <span></span>
</nav>

<style>
    .navbar {
        font-family: 'Silkscreen', cursive;
        background-color: #b36547;
        height: 80px;
        color: #00FF00;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .navbar > span {
        cursor: pointer;
        padding: 16px;
        font-size: 20px;
        display: flex;
        align-items: center;
    }

    span > img, span > span {
        width: 24px;
        height: 24px;
        margin-right: 8px;
    }
</style>
