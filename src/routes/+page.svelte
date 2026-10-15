<script>
  let { data } = $props()
</script>

<svelte:head><title>aap-example:sveltekit</title></svelte:head>

<main style="font-family: system-ui, sans-serif; margin: 3rem">
  <h1>SvelteKit</h1>
  <p>Rendered on the server at {data.rendered}. Marker: <code>aap-example:sveltekit</code></p>
</main>
