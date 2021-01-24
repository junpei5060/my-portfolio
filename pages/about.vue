<template>
  <div class="container">
    <header class="header">
      <nuxt-link to="/" class="link">Home</nuxt-link>
      <nuxt-link to="/garage" class="link">Garage</nuxt-link>
    </header>
    <h1 class="title">About</h1>
    <div class="icon">
      <a href="https://twitter.com/peipeijumpei"
        ><i class="fab fa-twitter-square"></i
      ></a>
      <a href="https://www.facebook.com/junpei.nakazawa.5/about">
        <i class="fab fa-facebook-square"></i
      ></a>
    </div>
    <div class="text">
      東京未来大学で大学職員をしながら、Web制作、動画編集をしております。
      プログラミング、動画編集等を初心者の方を対象にレクチャーしております
    </div>
    <div class="">
      <div class="imgtop">
        <img class="img" src="image/pro4.png" alt="" />
      </div>
      <div class="key">Name</div>
      <p class="value">Junpei Nakazawa</p>
      <div class="key">Contact</div>
      <p class="value">junpei.nakazawa.5060@gmail.com</p>
      <div class="key">Career</div>
      <p class="value">Meiho High School</p>
      <p class="value">Tokyo Keizai University</p>
      <p class="value">Tokyo Future University Staff</p>
      <div class="key">Areas of interest</div>
      <p class="value">Programming</p>
      <p class="value">Video editing</p>
      <p class="value">Education</p>
    </div>
    <div>
      <p class="text-dm">お仕事のご依頼はDMから</p>
      <div class="icon">
        <a href="https://twitter.com/peipeijumpei"
          ><i class="fab fa-twitter-square"></i
        ></a>
        <a href="https://www.facebook.com/junpei.nakazawa.5/about">
          <i class="fab fa-facebook-square"></i
        ></a>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css?family=Sacramento");
@import url("https://fonts.googleapis.com/css?family=Ubuntu+Mono");
.container {
  background-color: rgb(0, 0, 0);
  color: #ffffff;
}
.title {
  font-size: 32px;
  text-align: center;
  font-family: "Sacramento", cursive;
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

a {
  color: #000;
}

i {
  color: #ffffff;
}

.imgtop {
  text-align: center;
}
.img {
  width: 50%;
  opacity: 0.5;
}
.icon {
  text-align: center;
}
.fab {
  font-size: 28px;
}
.key {
  font-size: 20px;
  text-align: center;
  font-weight: bold;
  margin-top: 20px;
  font-family: "Sacramento", cursive;
}

.value {
  font-size: 16px;
  text-align: center;
  font-family: "Ubuntu Mono", monospace;
  margin-top: 5px;
}

.text-dm {
  font-size: 14px;
  text-align: center;
  width: 60%;
  margin: 20px auto 10px;
  font-family: "Ubuntu Mono", monospace;
  font-weight: bold;
}
</style>
