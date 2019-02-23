<template>
  <div class="work_history">
    <div class="column internal_one">
      <h2 class="font h2">Work Experience</h2>
    </div>
    <div class="column internal_two">
      <span class="display">
        <h3 class="font h4 display">Downvibe</h3>
        <span class="font light"> San Diego, CA, December 2018 - February 2019</span>
      </span>
      <p class="font text">
        Worked seamlessly with the team to create a flawless scalable backend. Utilizing my skillset to navigate a multilayered microservice architecture. Written in NodeJS. Jumping straight in and working on pre-existing structuring. Adapting to it smoothly, quickly, efficiently, and tirelessly.
        Independently created a beautiful, dare I say goregous frontend website, for users to interact with gaplessly. Allowing them to get lost in the product. Finding time to add beauty in the mechanisms of the aesthetics, utilizing the power of the VusJS framework. All while reaching my project leader's goals.
        Assisted with the systems administration. SSHing into a development VPS and staying within the bounds of the secure environment that was created.
        Overall, made massive improvements to the project. Reaching the desires of my project leader, as well as working independently to bring the project to heights and levels it could never have dreamed of on its own.
      </p>
    </div>
  </div>
</template>
<style scoped lang="scss">
@import "@/styles/constants.scss";

  .display {
    display: block;
  }
  @media screen and (min-width: #{$responsive_min_width}) {
    .display {
      display: inline;
    }
    .light {
      font-size: 16px;
    }
    .column {
      display: flex;
      flex-direction: column;
    }
    .work_history {
      display: flex;
    }
    .internal_one {
      width: 30%;
    }
    .internal_two {
      width: 70%;
    }
  }
</style>
