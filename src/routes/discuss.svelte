<script lang="ts">
  import Concords from "../components/concords.svelte";
  import Claims from "../components/claims.svelte";
</script>

<style>
  main {
    position: absolute;
    height: 100%;
    width: 100%;
    margin: 0;
    display: flex;
  }
  section {
    height: 100%;
    width: 50%;
    border: 1px dotted black;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>

<svelte:head>
  <title>Discuss to Understand and Find Agreements</title>
</svelte:head>
<main class="discuss">
  <section class="concords">
    <Concords />
  </section>
  <section class="claims">
    <Claims />
  </section>
</main>
