<script>
    import { kVotingSites } from "../../constants";
</script>

<main class="container">
    <button class="offset inverted" on:click={e => kVotingSites.forEach(uri => window.open(uri))}>
        Vote on All!
    </button>
    <p class="caption">
        Make sure to enable popups for this website!
        <a href="https://support.google.com/chrome/answer/95472" target="_blank" rel="noreferrer">See How</a>.
    </p>
    {#each kVotingSites as uri}
        <button class="offset" on:click={e => window.open(uri)}>
            Vote on { uri.slice(uri.indexOf("/") + 2, uri.indexOf("/", 9)) }
        </button>
    {/each}
</main>

<style>
    .caption {
        color: grey;
        text-align: center;
        margin: 0;
        margin-top: 16px;
        font-size: 0.8em;
    }

    button {
        --color: #ff0000;
        --hover: #00FF00;
        display: block;
        color: var(--color);
        transition: 0.25s;
        background: none;
        border: 2px solid;
        font: inherit;
        line-height: 1;
        margin: auto;
        margin-top: 2em;
        padding: 1em 2em;
        box-shadow: 0.3em 0.3em 0 0 var(--color), inset 0.3em 0.3em 0 0 var(--color);
    }
    button:hover, button:focus {
        border-color: var(--hover);
        color: #fff;
        box-shadow: 0 0 0 0 var(--hover), inset 6em 3.5em 0 0 var(--hover);
    }

    .inverted {
        --color: #8803fd;
        --hover: #00FF00;
    }
</style>
