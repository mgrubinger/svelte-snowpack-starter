<!-- App.svelte -->
<script>
  /* component logic will go here */
  let counter = 0;
</script>
<style>
  /* css will go here */
</style>
<div class="App">
  <h1>Hello Svelte</h1>
  <button type="button" on:click={() => counter++}>Click {counter}</button>
</div>