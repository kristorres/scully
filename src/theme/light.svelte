<script>
    import {LightTheme, css} from "svelte-doric"

    const custom = css`
        body {
            --torres-blue: #1a64d7;
            --torres-gold: #ffb500;

            --primary: var(--torres-blue);
            --primary-light: #4585e8;
            --primary-ripple: #1a64d760;
            --secondary: var(--torres-gold);
            --secondary-ripple: #ffb50060;
            --danger: #f44336;
            --danger-ripple: #f4433660;
            --background: #e3f2ff;
            --background-layer: white;

            --text-dark: #000000c0;
            --text-secondary: #00000080;
            --button-filled-text-color: var(--text-invert);
        }
    `
</script>

<LightTheme />
{@html custom}
