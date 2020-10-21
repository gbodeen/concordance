<script lang="ts">
  import Concords from "../components/concords.svelte";
  import Claims from "../components/claims.svelte";
  import Points from "../components/points.svelte";
</script>

<style>
  main.discuss {
    position: relative;
    height: 100%;
    width: 100%;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
  }
  section {
    height: 60%;
    width: 50%;
    border: 1px dotted black;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  section.write {
    height: 40%;
    width: 100%;
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
  <section class="write">
    <Points />
  </section>
</main>
