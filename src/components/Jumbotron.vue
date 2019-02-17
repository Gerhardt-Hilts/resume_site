<template>
    <div class="image_container">
      <img class="image" src="../assets/software.png">
      <p class="header">Looking for a fullstack developer?</p>
    </div>
</template>
<style>
  .image_container {
    position: relative;
    width: 100%;
    height: 500px;
    object-fit: cover;
    object-position: 50% 75%;
  }
  .image {
    position: absolute;
    width: 100%;
    height: 500px;
    object-fit: cover;
    object-position: 50% 75%;
  }
  .header {
    position: absolute;
    top: 50%;
    /* width: inherit; */
    white-space: nowrap;
    text-align: center;
    background-color: rgba(0, 0, 0, 0.4);
    padding: 5px;
    left: 50%;
    color: white;
    font-family: fantasy ,Source Sans Pro;
    font-weight: 600;
    font-size: 75px;
    transform: translate(-50%, -50%);
    letter-spacing: 10px;
  }
</style>
