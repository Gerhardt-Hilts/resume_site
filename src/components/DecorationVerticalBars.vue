<template>
  <div class="decoration">
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
<style scoped lang="scss">
  @import "@/styles/constants.scss";

  .decoration {
    // position: fixed;
    width: 100vw;
    margin: 0;
  }
  .drop_bars {
    height: $jumbotron_height;
    display: flex;
    align-items: stretch;
    flex: 3 0px;
    position: relative;
  }
  .vertical_bars {
    flex-grow: 1;
    display: flex;
    justify-content: space-around;
  }
  .vertical_bar_width {
    width: $bar_vertical_size;
  }
  .vertical_bar_length_one {
    height: calc(#{$jumbotron_height} * .35);
    // 0.35
  }
  .vertical_bar_length_two {
    height: calc(#{$jumbotron_height} * .5);
    // 0.5
  }
  .vertical_bar_length_three {
    height: calc(#{$jumbotron_height} * .62);
    // 0.62
  }
  .vertical_bar_length_four {
    height: calc(#{$jumbotron_height} * .73);
    // 0.73
  }
  .vertical_bar_length_five {
    height: calc(#{$jumbotron_height} * 1);
    // 1
  }
  .vertical_bar_length_six {
    height: calc(#{$jumbotron_height} * .55);
    // 0.55
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
