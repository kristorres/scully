<script>
    import {wsx} from "@axel669/zephyr"
</script>

<style>
    :global([ws-x~="theme[light]"]) {
        --torres-blue: #1a64d7;
        --torres-gold: #ffb500;

        --primary: var(--torres-blue);
        --primary-ripple: #1a64d760;
        --secondary: var(--torres-gold);
        --secondary-ripple: #ffb50060;
        --background: #e3f2ff;
        --background-layer: white;

        --text-dark: #000000c0;
        --text-color-secondary: #00000080;
    }
    :global([ws-x~="theme[dark]"]) {
        --torres-blue: #8dcbff;
        --torres-gold: #fee283;

        --primary: var(--torres-blue);
        --primary-ripple: #8dcbff60;
        --secondary: var(--torres-gold);
        --secondary-ripple: #fee28360;
        --background: #011627;
        --background-layer: #0e2232;

        --text-light: #ffffffc0;
        --text-color-secondary: #ffffff80;
    }
</style>

<svelte:body use:wsx={{theme: "light", "@app": true}} />
