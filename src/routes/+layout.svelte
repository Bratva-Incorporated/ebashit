<script lang="ts">
  import 'uno.css';
  import '@fontsource-variable/work-sans/wght.css';
</script>

<slot />

<svelte:head>
  <title>EBASHIT</title>
</svelte:head>

<style>
  :global(body, html) {
    margin: 0;
    padding: 0;
    overflow: hidden;
    height: 100%;
    font-family: 'Work Sans Variable', sans-serif;
  }
</style>
