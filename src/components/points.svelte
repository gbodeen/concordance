<script lang="ts">
  export let point: string = `Here is a point that I want to make, that you might accept
  as a concord.`;
  export let logic: string = `Here I make an argument in favor of the point, with reasons, evidence,
  clarifications, distinctions, and explanations however I please.`;
</script>

<style>
  .make-claim {
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
    box-sizing: border-box;
    display: inline-block;
    margin: 15px;
    padding: 15px;
    text-align: justify;
    border: 1px dotted gray;
    border-radius: 15px;
  }
  input.point {
    font-size: large;
  }
  textarea.logic {
    font-size: medium;
    resize: none;
    flex-grow: 1;
  }
  ::placeholder {
    white-space: normal;
  }
  hr {
    margin-left: 0;
    margin-right: 0;
  }
</style>

<div class="make-claim">
  <input type="text" class="point" placeholder={point} />
  <hr />
  <textarea class="logic" placeholder={logic} />
</div>
