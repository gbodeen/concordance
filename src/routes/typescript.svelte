<script lang="typescript">
  let text: string = "";

  function mutate(content: string): string {
    return content.toUpperCase().split("").reverse().join("");
  }
</script>

<svelte:head>
  <title>TypeScript support</title>
</svelte:head>

<textarea placeholder="There's nothing here yet" bind:value={text} />

<p>{mutate(text)}</p>
