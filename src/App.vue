<template>
  <div id="app">
    <div id="page">
      <DecorationVerticalBars id="position_vertical_bars" />
      <DecorationHorizontalBars />
      <Jumbotron text="Looking for a fullstack developer?"/>
      <div id="main_row">
        <div id="main_column">
          <div id="content">
            <Bio class="internal_padding" />
            <Technologies class="internal_padding" />
            <WorkHistory class="internal_padding" />
          </div>
        </div>
      </div>
      <Footer />
      <DecorationHorizontalBars />
    </div>
  </div>
</template>
<script>
import DecorationHorizontalBars from '@/components/DecorationHorizontalBars.vue';
import DecorationVerticalBars from '@/components/DecorationVerticalBars.vue';
import Jumbotron from '@/components/Jumbotron.vue';
import Bio from '@/components/Bio.vue';
import Technologies from '@/components/Technologies.vue';
import WorkHistory from '@/components/WorkHistory.vue';
import Footer from '@/components/Footer.vue';

export default {
  components: {
    DecorationHorizontalBars,
    DecorationVerticalBars,
    Jumbotron,
    Bio,
    Technologies,
    WorkHistory,
    // Demo
    Footer
  }
}
</script>
<style scoped lang="scss">
@import "@/styles/constants.scss";

#app {
  padding: 0px;
  margin: 0px;
}
#page {
  min-height: $responsive_min_height;
  width: 100%;
}

#position_vertical_bars {
  position: fixed;
  z-index: -1;
}

#main_row {
  display: flex;
  justify-content: center;
}
#main_column {
  display: flex;
  flex-direction: column;
}
#content {
  background-color: rgba(255, 255, 255, 0.75);
  @media screen and (min-width: #{$responsive_min_width}) {
    width: 60vw;
    padding: 50px;
    margin-top: 150px;
    margin-bottom: 150px;
  }
}

.internal_padding {
  padding: 10px;
  & * {
    padding: 7px 0 7px 0;
  }
}
</style>
