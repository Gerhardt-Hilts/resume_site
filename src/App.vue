<template>
  <div id="app">
    <div id="foreground_decoration">
      <DecorationHorizontalBars style="position: absolute; z-index: 100; width: 100%;"/>
    </div>
    <div id="background_decoration">
      <DecorationVerticalBars />
    </div>
    <div id="content">
      <router-view/>
    </div>
  </div>
</template>
<script>
  import DecorationHorizontalBars from '@/components/DecorationHorizontalBars.vue'
  import DecorationVerticalBars from '@/components/DecorationVerticalBars.vue'
  export default {
    components: {
      DecorationHorizontalBars,
      DecorationVerticalBars,
    }
  }
</script>
<style lang="scss">
#app {
  // font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // background-image: ;
  // text-align: center;
  // color: #2c3e50;
}
#background_decoration {
  z-index: -100;
  position: fixed;
  top: 0;
}
#content {
  z-index: 0;
  position: relative;
}
#foreground_decoration {
  z-index: 100;
  // position: fixed;
  // top: 0;
}
// #decoration {
//   padding: 30px;
//   a {
//     font-weight: bold;
//     color: #2c3e50;
//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>
