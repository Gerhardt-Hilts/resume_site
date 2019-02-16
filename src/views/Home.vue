<template>
  <div class="home">
    <Jumbotron />
    <div class="content">
      <div class="column main">
        <div class="row">
          <div class="column">
            <h1 class="font h1">Gerhardt Hilts</h1>
            <p class="font subtext">FULL STACK DEVELOPER<p>
            <p class="font text bio">I'm fantastic at this. You want me on your team. I will make your life easier. Your pipeline smoother. Your frontend prettier. Your backend sharper. I've done it before I'll do it again no sweat. There is always room for improvement. I'm the guy that finds out how to improve on perfection. Haven't reached a perfect product yet? I will take you there. Throw me at that horrifyingly complex project. I'll square it away so smoothly, you'll forget other shapes exist!
            So why is it that I'm so conclusive on my abilities?
            If you don't know what to think about what I've done, I'll tell you what to think. "WOW! This guy is in control. He's got it down. I'm bringing this guy on board asap!"
            Look at all this stuff I've done.</p>
          </div>
        </div>
        <div class="row">
          <div class="column internal_one">
            <h2 class="font h2">Work Experience</h2>
          </div>
          <div class="column internal_two">
          <h3 class="font h3">Downvibe</h3>
            <p class="font text">
              Worked seamlessly with the team to create a flawless scalable backend. Utilizing my skillset to navigate a multilayered microservice architecture. Written in NodeJS. Jumping straight in and working on pre-existing structuring. Adapting to it smoothly, quickly, efficiently, and tirelessly.
              Independently created a beautiful, dare I say goregous frontend website, for users to interact with gaplessly. Allowing them to get lost in the product. Finding time to add beauty in the mechanisms of the aesthetics, utilizing the power of the VusJS framework. All while reaching my project leader's goals.
              Assisted with the systems administration. SSHing into a development VPS and staying within the bounds of the secure environment that was created.
              Overall, made massive improvements to the project. Reaching the desires of my project leader, as well as working independently to bring the project to heights and levels it could never have dreamed of on its own.
            </p>
          </div>
        </div>
        <div class="row">
          <div class="column internal_one">
            <h2 class="font h2">Technologies</h2>
          </div>
          <div class="column internal_three">
            <h3 class="h3 font">DAY-TO-DAY COMFORT</h3>
            <ul class="text">
              <li class="font">NodeJS</li>
              <li class="font">Amazon Web Services</li>
              <li class="font">VueJS</li>
              <li class="font">ReactJS</li>
              <li class="font">Angular 2-7</li>
              <li class="font">Webstorm</li>
            </ul>
          </div>
          <div class="column internal_three">
            <h3 class="font h3">EXPERIENCE WITH</h3>
            <ul class="text">
              <li class="font">KoaJS</li>
              <li class="font">Consul (limited)</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Jumbotron from '@/components/Jumbotron.vue';

export default {
  name: 'home',
  components: {
    Jumbotron
  }
}
</script>
<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Catamaran|Source+Sans+Pro');
  .font {
    font-family: Source Sans Pro, Catamaran, 'Avenir', Helvetica, Arial, sans-serif;
    line-height: 28px;
  }
  .h1 {
    font-size: 36px;
    padding: 20px;
    letter-spacing: 5px;
  }
  .h2 {
    font-size: 26px;
    font-weight: 300;
    font-family: Catamaran;
    padding: 20px;
  }
  .h3 {
    font-size: 16px;
    letter-spacing: 2px;
    font-weight: 600;
    padding: 20px 20px 0px 20px;
    text-decoration: underline;
  }
  .bio {
    margin-top: 10px;
    margin-bottom: 70px;
  }
  .main {
    margin-top: 100px;
    margin-bottom: 100px;
    width: 70vw;
    padding: 5vw;
    background-color: rgba(255, 255, 255, 0.75);
  }
  .subtext {
    font-size: 20px;
    padding-left: 20px;
  }
  .content {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .column {
    display: flex;
    flex-direction: column;

  }
  .row {
    display: flex;
    width: 100%;
    // overflow: hidden;
  }
  .internal_one {
    width: 30%;
  }
  .internal_two {
    width: 70%;
  }
  .internal_three {
    width: 35%;
  }
  .text {
    padding: 20px;
  }
  ul {
    list-style: dot;
  }
  li {
    margin-left: 40px;
  }
</style>
