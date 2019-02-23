<template>
  <div class="technologies">
    <div class="column internal_one">
      <p class="font h2">Technologies</p>
    </div>
    <div class="column internal_two">
      <h4 class="h4 font">DAY-TO-DAY COMFORT</h4>
      <ul class="text">
        <li class="font">NodeJS</li>
        <li class="font">Amazon Web Services</li>
        <li class="font">Google Cloud</li>
        <li class="font">Digital Ocean</li>
        <li class="font">Version Control ( GIT )</li>
        <li class="font">SQL Languages</li>
        <li class="font">Ajax</li>
        <li class="font">ReactiveX</li>
        <li class="font">VueJS</li>
        <li class="font">Angular 2-7</li>
        <li class="font">ReactJS</li>
        <li class="font">PreactJS</li>
        <li class="font">Redux</li>
        <li class="font">D3JS</li>
        <li class="font">Shell Script</li>
        <li class="font">Haxe</li>
        <li class="font">Ionic 1-3</li>
        <li class="font">Ionic Native</li>
        <li class="font">Linux Environment</li>
        <li class="font">Cross-Browser Compatibility</li>
        <li class="font">Mobile First Thinking</li>
      </ul>
    </div>
    <div class="column internal_two">
      <h4 class="font h4">EXPERIENCE WITH</h4>
      <ul class="text">
        <li class="font">KoaJS</li>
        <li class="font">Consul (limited)</li>
        <li class="font">Golang</li>
        <li class="font">Python 2-3</li>
        <li class="font">Apache Beam (limited)</li>
        <li class="font">Java</li>
        <li class="font">C++</li>
        <li class="font">OpenGL</li>
        <li class="font">Vulkan</li>
        <li class="font">Haskell</li>
        <li class="font">Cordova</li>
        <li class="font">Stencil</li>
      </ul>
    </div>
  </div>
</template>
<style scoped lang="scss">
  @import "@/styles/constants.scss";

  .technologies {
    @media screen and (min-width: #{$responsive_min_width}) {
      display: flex;
      justify-content: space-between;
      .internal_one {
        width: 30%;
      }
      .internal_two {
        width: 35%;
      }
      li {
        margin-left: 18px;
      }
    }
  }
</style>
