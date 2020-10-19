<script lang="ts">
  export let point: string = `Here is the main point that I want to make, that might get accepted
  as a concord.`;
  export let logic: string = `Here I make an argument in favor of the point, with reasons, evidence,
  clarifications, distinctions, and explanations however I please.`;
</script>

<style>
  .claims {
    padding: 20px;
    font-size: medium;
  }
  .claims div {
    margin: 15px;
    padding: 15px;
  }
  .point {
    font-size: large;
  }
</style>

<div class="claims">
  <div class="point">{point}</div>
  <hr />
  <div class="logic">{logic}</div>
</div>
