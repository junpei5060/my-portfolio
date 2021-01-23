<template>
  <div>
    <div class="full">
      <video
        id="bg-video"
        src='movie/douga.png'
        poster='image/dark.png'
        autoplay
        muted
      ></video>
      <h1 class="h1">Junpei Nakazawa</h1>
      <h2>More memories for all education</h2>
      <div class="btn">
        <nuxt-link to="/about" class="btn-flat-border">About me</nuxt-link>
        <nuxt-link to="/garage" class="btn-flat-border1">Garage</nuxt-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css?family=Ubuntu+Mono");

.full {
}
#bg-video {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100vw;
  min-height: 100%;
  width: 100%;
  height: auto;
  z-index: -100;
  background: url('image/dark.png') no-repeat;
  background-size: cover;
  background-position: center center;
}

.h1 {
  margin: 0;
  position: absolute;
  top: calc(50% - 0.5em);
  width: 100%;
  text-align: center;
  line-height: 1;
  font-size: 8vw;
  /* font-family:"Yu Gothic", "游ゴシック", YuGothic, "游ゴシック体"; */
  font-family: "Ubuntu Mono", monospace;
  color: #fff;
  font-size: 64px;
  animation-name: fade-in1;
  animation-duration: 4s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-iteration-count: 1;
  animation-direction: normal;
  animation-fill-mode: forwards;
}
@keyframes fade-in1 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
h2 {
  margin: 80px 0 0 0;
  position: absolute;
  top: calc(50% - 0.5em);
  width: 100%;
  text-align: center;
  line-height: 1;
  font-size: 2vw;
  /* font-family:"Yu Gothic", "游ゴシック", YuGothic, "游ゴシック体"; */
  font-family: "Ubuntu Mono", monospace;
  color: #fff;
}

.btn-flat-border {
  display: inline-block;
  padding: 0.8em 4em;
  text-decoration: none;
  color: #ffffff;
  border: solid 2px #000000;
  border-radius: 3px;
  transition: 0.4s;
  /* margin-top: 3.5%;
  margin-left: 15%; */
  background-color: #000000;
  position: absolute;
  top: calc(65% - 0.5em);
  left: 35%;
  font-family: "Ubuntu Mono", monospace;
}

.btn-flat-border:hover {
  background: #000000;
  border: solid 2px #ffffff;
  color: white;
}

.btn-flat-border1 {
  display: inline-block;
  padding: 0.8em 4em;
  text-decoration: none;
  color: #ffffff;
  border: solid 2px #000000;
  border-radius: 3px;
  transition: 0.4s;
  /* margin-top: 3.5%;
  margin-left: 7%; */
  background-color: #000000;
  position: absolute;
  top: calc(65% - 0.5em);
  left: 50%;
  font-family: "Ubuntu Mono", monospace;
}

.btn-flat-border1:hover {
  background: #000000;
  border: solid 2px #919191;
  color: white;
}

@media (max-width: 1100px) {
  .btn-flat-border {
    padding: 0.8em 2em;
    text-decoration: none;
    color: #ffffff;
    border: solid 2px #000000;
    border-radius: 3px;
    transition: 0.4s;
    /* margin-top: 135%;
    margin-left: 20%; */
    background-color: #000000;
    position: absolute;
    top: calc(60% - 0.5em);
    left: 30%;
    font-weight: bold;
  }
  .btn-flat-border1 {
    padding: 0.8em 2em;
    text-decoration: none;
    color: #ffffff;
    border: solid 2px #000000;
    border-radius: 3px;
    transition: 0.4s;
    /* margin-top: 135%;
    margin-left: 20%; */
    background-color: #000000;
    position: absolute;
    top: calc(60% - 0.5em);
    left: 55%;
    font-weight: bold;
  }
}

@media (max-width: 479px) {
  .h1 {
    font-size: 8vw;
  }

  h2 {
    margin: 40px 0 0 0;
    font-size: 4vw;
  }

  .btn {
    display: flex;
  }

  .btn-flat-border {
    padding: 0.8em 2em;
    text-decoration: none;
    color: #ffffff;
    border: solid 2px #000000;
    border-radius: 3px;
    transition: 0.4s;
    /* margin-top: 135%;
    margin-left: 20%; */
    background-color: #000000;
    position: absolute;
    top: calc(63% - 0.5em);
    left: 20%;
    font-weight: bold;
  }

  .btn-flat-border:hover {
    background: #ffffff;
    border: solid 2px #000000;
    color: white;
  }
  .btn-flat-border1 {
    padding: 0.8em 2em;
    text-decoration: none;
    color: #ffffff;
    border: solid 2px #000000;
    border-radius: 3px;
    transition: 0.4s;
    /* margin-top: 135%;
    margin-left: 20%; */
    background-color: #000000;
    position: absolute;
    top: calc(63% - 0.5em);
    left: 50%;
    font-weight: bold;
  }

  .btn-flat-border1:hover {
    background: #ffffff;
    border: solid 2px #000000;
    color: white;
  }
}
</style>
