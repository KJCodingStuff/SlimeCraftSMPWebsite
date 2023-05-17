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
            It introduces many aspects from mods like custom enchants, terrain, dungeons and much more! <i>PS: A list of all important features will be at the bottom of this page.</i>
            <br/><br/>
            Now you maybe wondering how to join the server on your 10 year old PC... Do not worry, we got you covered!
            All the work is done by custom plugins[Some by me, Some by others]! That means you <b>do not need a single mod</b>.
            This was done considering many people like me would have old PCs and would not be willing to download mods because of performance reasons.
            <br/><br/>
            Now your next question might be - What about the people who do not have a PC themself? Do not worry, we got you covered too!
            We allow bedrock connections too! That means you could play on the server <b>even on your mobiles or consoles or xbox</b> etc.
            <br/><br/>
            Also unlike other servers we have <b>zero</b> Pay-To-Win aspects. <i>So your parents need not worry about you emptying their credit cards.</i>
            However we do allow donations at <a href="https://ko-fi.com/slimecraftsmp" target="_blank" rel="noreferrer">Kofi</a> to pay for server upkeep, hosting and plugin cost.
            <b>PS: Everything mentioned at Kofi can be obtained by playing the game.</b>
        </p>
    <br/>
    <img class="mc-emerald" src={McEmerald} alt="Minecraft emerald"/>
    <h1>What are the features of SlimeCraftSMP?</h1>
        <p>
            I will only be talking about the "main" features since I do not wanna bore you all.
            <br/>We support ALL <i>yes you heard me right</i> ALL versions from <b>1.16 to 1.19</b>!
            <br/>We also <b>support bedrock</b> edition! You can join using your mobile, xbox, nintendo switch, console etc.
            <br/>We also run on the best hardware [AMD Ryzen 5 5600X 6-Core Processor], so you will experience almost <b>no lag</b>!
        </p>
    <h2>We have-</h2>
        <ul>
            <li><b>Unique terrain</b> in the overworld, nether and the end! View pictures <span tabindex="0" class="link" on:click={() => navigateTo('gallery')} on:keypress={() => navigateTo('gallery')}>here</span>!</li>
            <li>Roughly <b>150 custom structures</b> to keep you entertained!</li>
            <li>Resource worlds that reset every month so you <b>never run out of resources!</b></li>
            <li>A skills plugin with <b>multiple skills and over 100 abilities!</b></li>
            <li><b>Custom enchants!</b> Get one or multiple of the OP enchants you like and dominate the server!</li>
            <li><b>Unique progression system</b> to help you progress through Slimefun quickly <b>without spending a single XP!</b></li>
            <li>Daily and Weekly quests to get you <b>free rewards!</b></li>
            <li>A head shop with <b>unique player heads</b> for all those builders out there who like their builds to be absolutely detailed and beautiful!</li>
            <li>Normal mobs too easy? We have <b>multiple custom dungeons with custom bosses!</b></li>
            <li>FREE rewards for voting! Get upto <b>~200 gems, 6x crate keys, voter rank and much more</b> for just entering your username!</li>
            <li>An active staff team from different parts of the world to help you <b>within 48 hours!</b></li>
            <li>A Discord &lt;-&gt; Minecraft linking system, Discord &lt;-&gt; Minecraft levelling system and also <b>Proximity VC!</b></li>
            <li>Our own <b>custom discord bot</b> that has a lot of functions!</li>
            <li>A plugin to claim land and prevent grief! This way you can <b>keep your loot safe</b> from all those sneaky robbers!</li>
            <li>A <b>teams plugin</b> for all those team players out there!</li>
            <li>Per-player-warp system. People can <b>set their own warps</b> that you can teleport to!</li>
            <li>Automatic chat games every 30 minutes which also give you <b>free rewards!</b></li>
            <li>A graves plugin so you <b>don't lose your stuff when you die!</b></li>
            <li>A jobs plugin. Choose one out of 12 jobs and <b>earn passive income.</b></li>
            <li>An auction house for <b>selling and bidding of items for in-game currency!</b></li>
            <li>A rankup system to <b>flex your progression on the server!</b></li>
            <li>Not a fan of PvP? You can turn off PvP and then <b>nobody can attack or kill you!</b></li>
            <li>A good enough anticheat to <b>detect those pesky cheaters.</b> You can enjoy without being disturbed by a hacker.</li>
            <li>An economy setup, a <b>centralized server shop</b> and many features that support player economy.</li>
            <li>A bank to <b>store your in-game currency safely!</b></li>
            <li>A chest shop plugin through which you can <b>create your own shops easily!</b></li>
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
        color: #0000FF;
        cursor: pointer;
    }
</style>
