<template>
  <div class="top_bar">
    <div class="blue"></div>
    <div class="green"></div>
    <div class="red"></div>
  </div>
</template>
<script>
  export default {

  }
</script>
<style lang="scss">
  @import "@/styles/constants.scss";
  .top_bar {
    height: $bar_horizontal_size;
    width: inherit;
    display: flex;
    align-items: stretch;
    flex: 3;
    position: relative;
    border: none;
  }
  .blue {
    background-image: linear-gradient(77deg, #4FB6BB, #17888D);
    flex-grow: 1;
    border: none;
  }
  .green {
    background-image: linear-gradient(77deg, #C2F366, #9AD922);
    flex-grow: 1;
    border: none;
  }
  .red {
    background-image: linear-gradient(77deg, #FF6F6B, #E92A25);
    flex-grow: 1;
    border: none;
  }
</style>
