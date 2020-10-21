<script lang="ts">
  export let point: string = `Here is a point that you want to make, that I might accept
  as a concord.`;
  export let logic: string = `Here you make an argument in favor of the point, with reasons, evidence,
  clarifications, distinctions, and explanations however you please.`;
</script>

<style>
  .view-claim {
    position: relative;
    height: 100%;
    overflow-y: auto;
    box-sizing: border-box;
    padding: 20px;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
  .point,
  .logic {
    display: inline-block;
    margin: 15px;
    padding: 15px;
    text-align: justify;
  }
  .point {
    font-size: large;
  }
  .logic {
    font-size: medium;
    flex-grow: 1;
  }
  hr {
    margin-left: 0;
    margin-right: 0;
  }
</style>

<div class="view-claim">
  <span class="point">{point}</span>
  <hr />
  <div class="logic">{logic}</div>
</div>
