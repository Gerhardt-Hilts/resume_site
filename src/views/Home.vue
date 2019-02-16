<template>
  <div class="home">
    <Jumbotron />
    
    <h1 class="font header">Gerhardt Hilts</h1>
    <p class="font">I'm fantastic at this. You want me on your team. I will make your life easier. Your pipeline smoother. Your frontend prettier. Your backend sharper. I've done it before I'll do it again no sweat. There is always room for improvement. I'm the guy that finds out how to improve on perfection. Haven't reached a perfect product yet? I will take you there. Throw me at that horrifyingly complex project. I'll square it away so smoothly, you'll forget other shapes exist!</p>
    <p class="font">So why is it that I'm so conclusive on my abilities?</p>
    <p class="font">If you don't know what to think about what I've done, I'll tell you what to think. "WOW! This guy is in control. He's got it down. I'm bringing this guy on board asap!"
    <p class="font">Look at all this stuff I've done.</p>
    <p class="font">At Downvibe I:</p>
    <ul>
      <li class="font">Worked seamlessly with the team to create a flawless scalable backend. Utilizing my skillset to navigate a multilayered microservice architecture. Written in NodeJS. Jumping straight in and working on pre-existing structuring. Adapting to it smoothly, quickly, efficiently, and tirelessly.</li>
      <li class="font">Independently created a beautiful, dare I say goregous frontend website, for users to interact with gaplessly. Allowing them to get lost in the product. Finding time to add beauty in the mechanisms of the aesthetics, utilizing the power of the VusJS framework. All while reaching my project leader's goals.</li>
      <li class="font">Assisted with the systems administration. SSHing into a development VPS and staying within the bounds of the secure environment that was created.</li>
      <li class="font">Overall, made massive improvements to the project. Reaching the desires of my project leader, as well as working independently to bring the project to heights and levels it could never have dreamed of on its own.</li>
    </ul>
    <p class="font">Here are just some of the tools used at Downvibe to create the excellency that it is.</p>
    <ul>
      <li class="font">Webstorm</li>
      <li class="font">Consul</li>
      <li class="font">Amazon Web Services</li>
      <li class="font">NodeJS</li>
      <li class="font">KoaJS</li>
      <li class="font">VueJS</li>
    </ul>
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
  .font {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
  }
  .header {
    font-size: 24px;
  }
  ul {
    list-style: dot;
  }
  li {
    margin-left: 40px;
  }
</style>
