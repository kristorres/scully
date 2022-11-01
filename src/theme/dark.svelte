<script>
    import {DarkTheme, css} from "svelte-doric"

    const custom = css`
        body {
            --background: black;

            --primary: #5cb6ff;
            --primary-light: #bbdeff;
            --primary-ripple: #5cb6ff60;
            --secondary: #fee283;
            --secondary-ripple: #fee28360;
        }
    `
</script>

<DarkTheme />
{@html custom}
