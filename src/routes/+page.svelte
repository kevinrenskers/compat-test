<script lang="ts">
  let count = 1;
</script>

<h1>Welcome to SvelteKit {count}</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>

<p>
  <button
    on:click={() => {
      count = count + 1;
    }}>Increase count</button
  >
</p>
