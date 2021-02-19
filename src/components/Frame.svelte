<script>
  import FrameBody from './FrameBody.svelte';
  import FrameHeader from './FrameHeader.svelte';
  import FrameTopBar from './FrameTopBar.svelte';
</script>

<div>
  <FrameTopBar />
  <FrameHeader />
  <FrameBody />
</div>

<style>
  div {
    background-color: var(--frame-background);
    height: 100%;
  }
</style>
