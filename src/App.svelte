<script>
  let msg = "Hello World!";
</script>

<main>
  <h1>{msg}</h1>
</main>

<style lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

  /* The CSS below is for demo purposes only. Tailwind can be used instead. */
  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
    font-family: monospace;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }
</style>
