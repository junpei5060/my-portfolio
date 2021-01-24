<template>
  <div class="container">
    <header class="header">
      <nuxt-link to="/" class="link">Home</nuxt-link>
      <nuxt-link to="/garage" class="link">About</nuxt-link>
    </header>
    <h1 class="title"><span>Garage</span></h1>
    <div class="icon">
      <a class="tag" href="https://twitter.com/peipeijumpei"
        ><i class="fab fa-twitter-square"></i
      ></a>
      <a class="tag" href="https://www.facebook.com/junpei.nakazawa.5/about">
        <i class="fab fa-facebook-square"></i
      ></a>
    </div>
    <div class="text">
      過去の実績を紹介します
    </div>
    <div class="img-text">
      <div class="imgtop">
        <a href="https://junpei5060.github.io/meeeLook/"
          ><img class="img" src="image/garage1.png" alt=""
        /></a>
      </div>
      <div class="img2">
        <a href="https://meeelook.herokuapp.com"
          ><img class="img3" src="image/garage2.png" alt=""
        /></a>
        <a href="https://gyazo.com/1770ca05f61a46290c36b4022e7e565b"
          ><img class="img4" src="image/garage3.png" alt=""
        /></a>
      </div>
    </div>
    <div>
      <h2>More memories for all education</h2>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css?family=Sacramento");
@import url("https://fonts.googleapis.com/css?family=Ubuntu+Mono");

.container {
  background-color: rgb(0, 0, 0);
  color: #ffffff;
  animation-name: fade-in1;
  animation-duration: 4s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-iteration-count: 1;
  animation-direction: normal;
  animation-fill-mode: forwards;
  height: 100vh;
}
@keyframes fade-in1 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
.title {
  font-size: 32px;
  text-align: center;
  font-family: "Sacramento", cursive;
  position: relative;
}

.title span span {
  font-size: 18px;
  font-size: 1.8rem;
  display: block;
}

.title:before {
  position: absolute;
  bottom: 1px;
  left: calc(50% - 30px);
  width: 60px;
  height: 2px;
  content: "";
  border-radius: 3px;
  background: #ffffff;
}

.text {
  font-size: 14px;
  text-align: center;
  width: 60%;
  margin: 10px auto;
  font-family: "Ubuntu Mono", monospace;
}

.header {
  text-align: center;
  margin-bottom: 10px;
  border-bottom: 1px solid rgb(162, 162, 162);
}

.link {
  color: #ffffff;
  text-decoration: none;
  font-family: "Sacramento", cursive;
  cursor: pointer;
  font-weight: bold;
  font-size: 18px;
  margin-left: 10px;
}

.tag {
  color: #000;
}

i {
  color: #ffffff;
  margin-top: 30px;
}

.imgtop {
  text-align: center;
}
.img {
  width: 80%;
  opacity: 0.8;
  transition: 1s;
  box-shadow: 0 1px 10px #ccc;
}
img:hover {
  opacity: 1;
}
.img3 {
  width: 80%;
  opacity: 0.8;
  transition: 1s;
  box-shadow: 0 1px 10px #ccc;
  margin-top: 5px;
}
.img3:hover {
  opacity: 1;
}
.img4 {
  width: 80%;
  opacity: 0.8;
  transition: 1s;
  box-shadow: 0 1px 10px #ccc;
  margin-top: 5px;
}
.img4:hover {
  opacity: 1;
}

.img2 {
  text-align: center;
}

.icon {
  text-align: center;
  font-size: 12px;
}
.fab {
  font-size: 28px;
}

h2 {
  margin: 50px 0 0 0;
  width: 100%;
  text-align: center;
  line-height: 1;
  font-size: 4vw;
  /* font-family:"Yu Gothic", "游ゴシック", YuGothic, "游ゴシック体"; */
  font-family: "Sacramento", cursive;
  color: #fff;
}

@media screen and (min-width: 831px) {
  .container {
    min-height: 100%;
    height: 100vh;
  }
  .header {
    text-align: center;
    margin-bottom: 10px;
    border-bottom: 1px solid rgb(162, 162, 162);
    height: 50px;
    line-height: 50px;
  }
  .link {
    color: #ffffff;
    text-decoration: none;
    font-family: "Sacramento", cursive;
    cursor: pointer;
    font-weight: bold;
    font-size: 24px;
    margin-left: 10px;
  }

  .title {
    font-size: 62px;
    text-align: center;
    font-family: "Sacramento", cursive;
  }
  .text {
    font-size: 20px;
    text-align: center;
    width: 50%;
    margin: 30px auto 60px;
    font-family: "Ubuntu Mono", monospace;
  }
  .img {
    width: 20%;
    opacity: 0.5;
    box-shadow: 0 2px 15px #ccc;
  }
  .img3 {
    width: 40%;
    opacity: 0.5;
    box-shadow: #ffffff;
    margin-top: 50px;
    box-shadow: 0 2px 15px #ccc;
  }
  .img4 {
    width: 45%;
    opacity: 0.5;
    box-shadow: #ffffff;
    margin-top: 50px;
    box-shadow: 0 2px 15px #ccc;
  }
  .img2 {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .img-text {
    margin-bottom: 50px;
    width: 100%;
  }
  .imgtop {
    text-align: center;
  }
  .text-dm {
    font-size: 20px;
    text-align: center;
    width: 60%;
    margin: 20px auto 10px;
    font-family: "Ubuntu Mono", monospace;
    font-weight: bold;
  }
  i {
    color: #ffffff;
    font-size: 20px;
  }
  h2 {
    margin: 3px 0 0 0;
    width: 100%;
    text-align: center;
    line-height: 1;
    font-size: 1vw;
    /* font-family:"Yu Gothic", "游ゴシック", YuGothic, "游ゴシック体"; */
    font-family: "Sacramento", cursive;
    color: #fff;
  }
}
@media screen and (min-width: 481px) and (max-width: 830px) {
  .container {
    min-height: 100%;
    height: 100vh;
  }

  .header {
    text-align: center;
    margin-bottom: 10px;
    border-bottom: 1px solid rgb(162, 162, 162);
    height: 30px;
    line-height: 30px;
  }
  .link {
    color: #ffffff;
    text-decoration: none;
    font-family: "Sacramento", cursive;
    cursor: pointer;
    font-weight: bold;
    font-size: 16px;
    margin-left: 10px;
  }

  .title {
    font-size: 16px;
    text-align: center;
    font-family: "Sacramento", cursive;
  }
  .text {
    font-size: 8px;
    text-align: center;
    width: 50%;
    margin: 10px auto 20px;
    font-family: "Ubuntu Mono", monospace;
  }
  .img {
    width: 20%;
    opacity: 0.5;
    margin-left: 240px;
    box-shadow: #ffffff;
  }
  .img-text {
    display: flex;
    margin-bottom: 30px;
    width: 70%;
  }
  .text-dm {
    font-size: 14px;
    text-align: center;
    width: 60%;
    margin: 20px auto 10px;
    font-family: "Ubuntu Mono", monospace;
    font-weight: bold;
  }
  i {
    color: #ffffff;
    font-size: 10px;
  }
  .icon {
    font-size: 20px;
  }
  .fab {
    font-size: 18px;
    margin: 0;
  }
  .key {
    font-size: 8px;
    text-align: center;
    font-weight: bold;
    margin-top: 1px;
    font-family: "Sacramento", cursive;
  }

  .value {
    font-size: 8px;
    text-align: center;
    font-family: "Ubuntu Mono", monospace;
    margin-top: 1px;
  }
  .text-dm {
    font-size: 10px;
    text-align: center;
    width: 60%;
    margin: 2px auto 2px;
    font-family: "Ubuntu Mono", monospace;
    font-weight: 100;
  }
  .img-text {
    margin: 0;
  }
}
</style>
