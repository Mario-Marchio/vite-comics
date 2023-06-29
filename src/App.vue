<script>
export default {
  data() {
    return {
      navTexts: [
        {
          text: 'Characters',
          url: '#',
          current: false,
        },
        {
          text: 'Comics',
          url: '#',
          current: true,
        },
        {
          text: 'Movies',
          url: '#',
          current: false,
        },
        {
          text: 'TV',
          url: '#',
          current: false,
        },
        {
          text: 'Games',
          url: '#',
          current: false,
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false,
        },
        {
          text: 'Videos',
          url: '#',
          current: false,
        },
        {
          text: 'Fans',
          url: '#',
          current: false,
        },
        {
          text: 'News',
          url: '#',
          current: false,
        },
        {
          text: 'Shop',
          url: '#',
          current: false,
        },
      ],

    }
  },
  components: {

  }
}
</script>
<template>
  <header>
    <div class="h-30 bgc-black"></div>
    <div class="container header-nav">
      <figure>
        <img class="p-10" src="./assets/img/dc-logo.png" alt="dc-logo">
      </figure>
      <div class="r-header-nav">
        <ul>
          <li v-for="navText in navTexts">
            <a class="color-black px-55 py-5 " href="#">{{ navText.text.toUpperCase() }}</a>
          </li>
        </ul>
      </div>
    </div>
    <div class="bgc-black ">
      <div class="container content">
        content goes here
      </div>
    </div>
  </header>
  <main>
    <div class="bgc-l-blue">
      <div class="container nav-main">
        <ul>
          <li class="nav-main-li">
            <img class="nav-main-img" src="./assets/img/buy-comics-digital-comics.png" alt="">
            <a class="nav-main-a" href="#">DIGITAL COMICS</a>
          </li>
          <li class="nav-main-li">
            <img class="nav-main-img" src="./assets/img/buy-comics-merchandise.png" alt="">
            <a class="nav-main-a" href="#">DC MERCHANDISE</a>
          </li>
          <li class="nav-main-li">
            <img class="nav-main-img" src="./assets/img/buy-comics-subscriptions.png" alt="">
            <a class="nav-main-a" href="#">SUBSCRIPTION</a>
          </li>
          <li class="nav-main-li">
            <img class="nav-main-img" src="./assets/img/buy-comics-shop-locator.png" alt="">
            <a class="nav-main-a" href="#">COMIC SHOP LOCATOR</a>
          </li>
          <li class="nav-main-li">
            <img class="nav-main-img" src="./assets/img/buy-dc-power-visa.svg" alt="">
            <a class="nav-main-a" href="#">DC POWER VISA</a>
          </li>
        </ul>
      </div>
    </div>
  </main>
  <footer>

  </footer>
</template>
<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  height: auto;
  max-width: 100%;
}

li {
  list-style-type: none;
  align-items: center;
  display: flex;
}

ul {
  display: flex;
}

a {
  text-decoration: none;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}

.h-30 {
  height: 30px;
}

.p-10 {
  padding: 10px;
}

.px-55 {
  padding: 55px 0;
}

.py-5 {
  padding: 0 5px;
}

.bgc-black {
  background-color: black;
}

.bgc-l-blue {
  background-color: #0282F9;
}

.color-black {
  color: black;
}

.header-nav {
  display: flex;
  justify-content: space-between;
}

.r-header-nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.content {
  color: white;
  display: flex;
  align-items: center;
  height: 120px;
  font-size: x-large;
}

.nav-main {
  height: 150px;
  display: flex;
  align-items: center;
  color: white;
}

.nav-main-img {
  height: 50px;
}

.nav-main-a {
  color: white;
  padding: 0 10px;
  white-space: nowrap;
}

.nav-main-li {
  padding: 0 30px;
}
</style>