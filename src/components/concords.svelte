<script lang="ts">
  export let concords: string[] = [
    "This is an already-agreed-upon statement.",
    "So is this.",
    "Here's one more",
  ];
</script>

<style>
  .concords {
    position: relative;
    height: 100%;
    overflow-y: auto;
    box-sizing: border-box;
    padding: 20px;
  }
  ol {
    margin: 0;
    padding: 0;
  }
  li {
    margin: 15px;
    padding: 15px;
    border: 1px dotted gray;
    border-radius: 15px;
    font-size: medium;
  }
</style>

<div class="concords">
  <ol>
    {#each concords as concord}
      <li>{concord}</li>
    {/each}
  </ol>
</div>
