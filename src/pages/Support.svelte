<script>
    import McGrassBlock from "../assets/mc-grass-block.svg";
    export let navigateTo;

    const guidelinesUri = 'https://discord.com/channels/1074746940253802556/1074746941528879150/1096754824000835664';
    const staffTicketUri = 'https://discord.com/channels/1074746940253802556/1074746941528879150/1096754895354335242';
    const donateTicketUri = 'https://discord.com/channels/1074746940253802556/1074746941528879150/1096755000048357476';
    const bugTicketUri = 'https://discord.com/channels/1074746940253802556/1074746941528879150/1096755128419225670';
    const hackerTicketUri = 'https://discord.com/channels/1074746940253802556/1074746941528879150/1096755264511803444';
    const questionTicketUri = 'https://discord.com/channels/1074746940253802556/1074746941528879150/1096755383479054377';
    const discordInvite = 'https://discord.gg/xFtghGVCVD';
</script>

<main class="container">
    <img class="mc-grass-block" src={McGrassBlock} alt="Minecraft grass block"/>
    <br/>

    <h1>Support Guidelines</h1>
        <p>
            Need help? You can create a ticket on our <a href={discordInvite} target="_blank" rel="noreferrer">discord server</a>!
            There are some <a href={guidelinesUri}>guidelines</a> though.
        </p>
    <br/>
    <h2>Help! A Staff is abusing his/her powers!</h2>
        <p>
            Found a staff abusing his/her powers? Have an issue with how one handed a situation?
            <br/>You can <a href={staffTicketUri} target="_blank" rel="noreferrer">create a ticket</a>!
            <br/>Handled by an Manager+ , if you have an issue with an Manager+ please DM PhoenixPlayz#1880.
        </p>
    <br/>
    <h2>I donated but did not get my rank! You scammer!</h2>
        <p>
            Did you donate but did not get your perks? Did you not recieve a rank/item you won from giveaway?
            <br/>You can <a href={donateTicketUri} target="_blank" rel="noreferrer">create a ticket</a>!
            <br/>Do not worry! It happens sometimes due to unavoidable situations. Your rank/items will be given!
        </p>
    <br/>
    <h2>I found a game-breaking bug! This stuff does not work!</h2>
        <p>
            Found a dupe/exploit in game? Did you lose items due to a bug?
            <br/>You can <a href={bugTicketUri} target="_blank" rel="noreferrer">create a ticket</a>!
            <br/>The bugs will be confirmed by staff and fixed by PhoenixPlayz#1880! Thank you for reporting and keeping the server safe!
        </p>
    <br/>
    <h2>This player is being toxic! Hacker! Help!</h2>
        <p>
            Found a hacker? Found a player breaking the server
            <span tabindex="0" class='link' on:click={() => navigateTo('rules')} on:keypress={() => navigateTo('rules')}>rules</span>?
            Your base was griefed?
            <br/>You can <a href={hackerTicketUri} target="_blank" rel="noreferrer">create a ticket</a>!
            <br/>The player will be muted/banned. Grief will be rolled back. Your items will be refunded!
        </p>
    <br/>
    <h2>Oh I just have a question!</h2>
        <p>
            Have some questions about the server? Something that does not fit any other category?
            <br/>You can <a href={questionTicketUri} target="_blank" rel="noreferrer">create a ticket</a>!
            <br/>Your questions will be answered within 24 hours
        </p>
    <br/><br/>
    <div class="blue-glow">
        Website by <a href="https://github.com/PhoenixCodingStuff" target="_blank" rel="noreferrer">PhoenixCodingStuff</a>
        and <a href="https://mitulagr2.netlify.app/" target="_blank" rel="noreferrer">mitulagr2</a>!
        <br/> Feel free to drop by with any concerns or if you like the website :)
    </div>
    <br/>
</main>

<style>
    iframe {
        display: block;
        margin: 0 auto;
    }

    .mc-grass-block {
        position: absolute;
    }

    .link {
        color: #0000FF;
        cursor: pointer;
    }

    .blue-glow {
        color: #0000FF;
        text-shadow: 0 0 4px rgba(119, 119, 255, 170);
    }
</style>
