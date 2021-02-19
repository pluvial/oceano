<script></script>

<main><slot /></main>

<style>
  :root {
    /* font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, */
      /* Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif; */
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol";
    --sidebar-background: rgb(55, 60, 63);
    --frame-background: rgb(47, 52, 55);
    background-color: var(--frame-background);
  }

  :global(body) {
    margin: 0;
  }

  main {
    height: 100vh;
    display: flex;
    flex: 1 1 0%;
  }
</style>
