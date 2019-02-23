<template>
    <div class="image_container">
      <img class="image" src="../assets/software.png">
      <p class="header">{{ text }}</p>
    </div>
</template>
<script>
  export default {
    props: {
      text: {
        type: String
      }
    }
  }
</script>
<style lang="scss" scoped>
  @import "@/styles/constants.scss";
  .image_container {
    position: relative;
    width: $jumbotron_width;
    height: $jumbotron_height;
  }
  .image {
    position: absolute;
    width: $jumbotron_width;
    height: $jumbotron_height;
    object-fit: cover;
  }
  .header {
    margin: 0;
    padding: 5px 0 5px 0;
    position: absolute;
    width: inherit;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    font-family: $fonts;
    background-color: rgba(0, 0, 0, 0.4);
    color: white;
    font-size: 6vw;
    @media screen and (min-width: #{$responsive_min_width}) {
      font-size: 48px;
    }
  }
  // .header {
  //   position: absolute;
  //   top: 50%;
  //   /* width: inherit; */
  //   white-space: nowrap;
  //   text-align: center;
  //   padding: 5px;
  //   left: 50%;
  //   color: white;
  //   font-family: Source Sans Pro, Catamaran, 'Avenir', Helvetica, Arial, sans-serif;
  //   font-weight: 600;
  //   font-size: 75px;
  //   transform: translate(-50%, -50%);
  //   letter-spacing: 10px;
  // }
  // @media screen and (max-width: 650px) {
  //   .header {
  //     font-size: 20px;
  //     letter-spacing: normal;
  //   }
  // }
</style>
