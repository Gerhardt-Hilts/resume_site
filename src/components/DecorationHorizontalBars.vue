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
<style>
  .decoration {
    position: fixed;
    width: 100vw;
  }
  .top_bar {
    height: 25px;
    width: inherit;
    background-color: magenta;
    display: flex;
    align-items: stretch;
    flex: 3 0px;
    position: relative;
  }
  .blue {
    background-image: linear-gradient(77deg, #4FB6BB, #17888D);
    flex-grow: 1;
  }
  .green {
    background-image: linear-gradient(77deg, #C2F366, #9AD922);
    flex-grow: 1;
  }
  .red {
    background-image: linear-gradient(77deg, #FF6F6B, #E92A25);
    flex-grow: 1;
  }
</style>
