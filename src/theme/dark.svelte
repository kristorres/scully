<script>
    import {DarkTheme, css} from "svelte-doric"

    const custom = css`
        body {
            --torres-blue: #8dcbff;
            --torres-gold: #fee283;

            --primary: var(--torres-blue);
            --primary-light: #f0f8ff;
            --primary-ripple: #8dcbff60;
            --secondary: var(--torres-gold);
            --secondary-ripple: #fee28360;
            --danger: #ef9a9a;
            --danger-ripple: #ef9a9a60;
            --background: #011627;
            --background-layer: #0e2232;

            --text-light: #ffffffc0;
            --text-secondary: #ffffff80;
            --button-filled-text-color: var(--text-invert);
        }
    `
</script>

<DarkTheme />
{@html custom}
