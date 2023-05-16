<script>
    import McLogo from "../assets/mc-logo.svg";
    import McEmerald from "../assets/mc-emerald.png";
    export let navigateTo;
</script>

<main class="container">
    <img class="mc-logo" src={McLogo} alt="Minecraft logo art"/>
    <h1>What is SlimeCraftSMP?</h1>
        <p>
            SlimeCraftSMP is a <b>Public Minecraft Server</b> which attempts to make Minecraft a bit more fun for people who are bored for Vanilla Minecraft.
            It introduces many aspects from mods like enchants terrain etc. I will not waste your time with all features and leave that for later.
            <br/><br/>
            Now you maybe wondering how to join the server on your 10 year old PC... Do not worry , we got you covered!
            All the work is done by custom plugins[Some by me , Some by others]! That means you <b>do not need a single mod</b>.
            This was done considering many people like me would have old PCs and would not be willing to download mods because of performance reasons.
            <br/><br/>
            Now your next question might be - What about the people who do not have a PC themself? Do not worry , we got you covered too!
            We allow bedrock connections too! That means you could play on the server <b>even on your mobiles or consoles or xbox</b> etc.
            <br/><br/>
            Also unlike other servers we have <b>zero</b> Pay-To-Win aspects. <i>So your parents need not worry about you emptying their credit cards.</i>
        </p>
    <br/>
    <img class="mc-emerald" src={McEmerald} alt="Minecraft emerald"/>
    <h1>What are the features of SlimeCraftSMP?</h1>
        <p>
            I will only be talking about the "main" features since I do not wanna bore you all.
            <br/>We support ALL <i>yes you heard me right</i> ALL versions from <b>1.16 to 1.19</b>!
            <br/>We also <b>support bedrock</b> edition! You can join using your mobile , xbox , nintendo switch , console etc.
            <br/>We also run on the best hardware [AMD Ryzen 5 5600X 6-Core Processor] , so you will experience almost <b>no lag</b>!
        </p>
    <h2>We have-</h2>
        <ul>
            <li><b>Custom terrain</b> in the overworld , nether and the end! View pictures <span tabindex="0" class="link" on:click={() => navigateTo('gallery')} on:keypress={() => navigateTo('gallery')}>here</span>!</li>
            <li>About 150 structures to keep you entertained!</li>
            <li>Resource worlds that reset every month so you never run out of resources!</li>
            <li>A bank to store your money safely!</li>
            <li>An <b>active staff</b> team from different parts of the world to help you within 24 hours!</li>
            <li>A <b>skills plugin</b> with multiple skills and over 100 abilities!</li>
            <li><b>Custom enchants</b>! Get one or multiple of the OP enchants you like and dominate the server!</li>
            <li>Custom advancements to help you progress quickly!</li>
            <li>A Discord &lt;-&gt; Minecraft linking system , Discord &lt;-&gt; Minecraft levelling system and also Proximity VC!</li>
            <li>Our own <b>custom discord bot</b> that has a lot of functions!</li>
            <li>Daily and Weekly quests!</li>
            <li>A plugin to claim land and <b>prevent grief</b>. This way you can keep your loot safe from all those sneaky robbers.</li>
            <li>A <b>teams plugin</b> for all those team players out there.</li>
            <li>Per-player-warp system. People can <b>set their own warps</b> that you can teleport to!</li>
            <li>Automatic chat games every 30 minutes!</li>
            <li>An economy setup , a centralized <b>server shop</b> and many features that support player economy.</li>
            <li>A head shop for all those builders out there who like their builds to be absolutely detailed and beautiful!</li>
            <li>A <b>graves plugin</b> so you don't lose your stuff when you die!</li>
            <li>A jobs plugin. Choose one out of <b>12 jobs</b> and earn passive income.</li>
            <li>An <b>auction house</b> for selling and bidding of items.</li>
            <li>A chest shops plugin. Players can <b>create their own shops</b>!</li>
            <li>A rankup system to flex your progression on the server!</li>
            <li>Normal mobs too easy? We have 6 dungeons with custom bosses!</li>
            <li>Not a fan of PvP? You can turn off PvP and then nobody can attack you and kill you.</li>
            <li>A good enough <b>anticheat</b> to detect and ban those pesky cheaters. You can enjoy without being disturbed by a hacker.</li>
            <li><b>FREE</b> rewards for voting!.</li>
        </ul>
</main>

<style>
    .mc-logo {
        position: absolute;
        right: -64px;
    }
    .mc-emerald {
        position: absolute;
        left: -32px;
        transform: rotate(10deg);
    }
    .link {
        color: #ffb084;
        cursor: pointer;
    }
</style>
