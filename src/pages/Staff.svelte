<script>
  import CreeperSplash from "../assets/creeper-splash.png";
  import { kStaffList } from "../../constants";
</script>

<main class="container">
    {#each kStaffList as list}
        <h1 style="color:{list.color};"> {list.role}</h1>

        <p style="color:{list.color};">
            {#each list.members as member}
                <p>{member.IGN} / {member.username}</p>
            {/each}
            {#if list.members.length == 0}
                <p>None. You can apply by creating a ticket on discord!</p>
            {/if}
        </p>

        {#if list.role == "Admins"}
            <img class="creeper-splash" src={CreeperSplash} alt="Minecraft creeper art"/>
        {/if}
        <br/>
    {/each}
</main>

<style>
    .container {
        text-align: center;
    }
    
    .creeper-splash {
        position: absolute;
        right: -216px;
        height: 450px;
        width: 600px;
    }

    p > p {
        margin: 0
    }
</style>
