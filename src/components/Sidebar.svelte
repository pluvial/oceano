<script>
</script>

<div><slot /></div>

<style>
  div {
    background-color: var(--sidebar-background);
    width: 240px;
    height: 100%;
    flex-grow: 0;
    flex-shrink: 0;

    transition: box-shadow 300ms ease-in 0s;
    pointer-events: none;
    position: relative;
    z-index: 99;
  }
</style>
