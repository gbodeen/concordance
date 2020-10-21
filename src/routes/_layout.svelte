<script lang="ts">
  import Nav from "../components/Nav.svelte";

  export let segment: string;
</script>

<style>
  .innerbody {
    position: absolute;
    height: 100vh;
    width: 100vw;
    display: flex;
    flex-direction: column;
  }
  main {
    flex-grow: 1;
  }
</style>

<div class="innerbody">
  <Nav {segment} />
  <main>
    <slot />
  </main>
</div>
