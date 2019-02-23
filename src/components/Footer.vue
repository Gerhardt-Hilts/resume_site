<template>
  <div class="footer">
    <div class="contact">
      <div class="light_column">
        <div class="font h1">Hire your new</div>
        <div class="font h1">fullstack developer</div>
        <div class="font h1">of choice today!</div>
      </div>
      <div class="font light">Come say, hello world!</div>
      <div class="light_column">
        <div class="font light">405-532-9839</div>
        <div class="font light"> | gerhardthilts@gmail.com | </div>
        <div class="font light">gerhardthilts.com</div>
      </div>
    </div>
  </div>
</template>
<style scoped lang="scss">
  @import "@/styles/constants.scss";

  .contact {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #fff;
    // width: 100vw;
    height: 110vh;
    margin-top: -5px;
  }
  .light_column {
    display: flex;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    align-items: center;
    @media screen and (min-width: 1300px) {
      display: flex;
      flex-direction: row;
    }
  }
  .h1 {
    margin: 0;
    line-height: normal;
    white-space: nowrap;
    padding: 5px;
    text-align: center;
    font-family: $fonts;
    font-size: 6vw;
    @media screen and (min-width: #{$responsive_min_width}) {
      font-size: 48px;
    }
  }
</style>
