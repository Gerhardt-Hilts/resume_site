<template>
  <div class="decoration">
    <div class="top_bar">
      <div class="blue"></div>
      <div class="green"></div>
      <div class="red"></div>
    </div>
    <div class="drop_bars">
      <div class="vertical_bars">
        <div class="vertical_bar_length_four vertical_bar_width vertical_bar_blue"></div>
        <div class="vertical_bar_length_six vertical_bar_width vertical_bar_blue"></div>
        <div class="vertical_bar_length_three vertical_bar_width vertical_bar_blue"></div>
        <div class="vertical_bar_length_five vertical_bar_width vertical_bar_blue"></div>
        <div class="vertical_bar_length_one vertical_bar_width vertical_bar_blue"></div>
        <div class="vertical_bar_length_two vertical_bar_width vertical_bar_blue"></div>
      </div>
      <div class="vertical_bars">
        <div class="vertical_bar_length_four vertical_bar_width vertical_bar_green"></div>
        <div class="vertical_bar_length_six vertical_bar_width vertical_bar_green"></div>
        <div class="vertical_bar_length_five vertical_bar_width vertical_bar_green"></div>
        <div class="vertical_bar_length_two vertical_bar_width vertical_bar_green"></div>
        <div class="vertical_bar_length_one vertical_bar_width vertical_bar_green"></div>
        <div class="vertical_bar_length_three vertical_bar_width vertical_bar_green"></div>
      </div>
      <div class="vertical_bars">
        <div class="vertical_bar_length_one vertical_bar_width vertical_bar_red"></div>
        <div class="vertical_bar_length_three vertical_bar_width vertical_bar_red"></div>
        <div class="vertical_bar_length_five vertical_bar_width vertical_bar_red"></div>
        <div class="vertical_bar_length_four vertical_bar_width vertical_bar_red"></div>
        <div class="vertical_bar_length_two vertical_bar_width vertical_bar_red"></div>
        <div class="vertical_bar_length_six vertical_bar_width vertical_bar_red"></div>
      </div>
    </div>
  </div>
</template>
<style lang="scss">
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
  .drop_bars {
    height: 500px;
    display: flex;
    align-items: stretch;
    flex: 3 0px;
    position: relative;
    z-index: -100px;
  }
  .vertical_bars {
    flex-grow: 1;
    display: flex;
    justify-content: space-around;
  }
  .vertical_bar_width {
    width: 1.4vw;
  }
  .vertical_bar_length_one {
    height: 175px;
  }
  .vertical_bar_length_two {
    height: 250px;
  }
  .vertical_bar_length_three {
    height: 365px;
  }
  .vertical_bar_length_four {
    height: 310px;
  }
  .vertical_bar_length_five {
    height: 500px;
  }
  .vertical_bar_length_six {
    height: 275px;
  }
  .vertical_bar_blue {
    background-color: #4FB6BB;
  }
  .vertical_bar_green {
    background-color: #C2F366;
  }
  .vertical_bar_red {
    background-color: #FF6F6B;
  }
</style>
