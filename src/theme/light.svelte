<script>
    import {LightTheme, css} from "svelte-doric"

    const custom = css`
        body {
            --background: #eceff1;

            --primary: #1a64d7;
            --primary-light: #8dbcff;
            --primary-ripple: #1a64d760;
            --secondary: #ffb500;
            --secondary-ripple: #ffb50060;
        }
    `
</script>

<LightTheme />
{@html custom}
