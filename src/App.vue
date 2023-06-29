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
          <li>
            <a class="color-black px-55 py-5 " href="#">CHARATCTERS</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">COMICS</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">MOVIES</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">TV</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">GAMES</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">COLLECTIBLES</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">VIDEOS</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">FANS</a>
          </li>
          <li>
            <a class="color-black px-55 py-5" href="#">NEWS</a>
          </li>
          <li>

            <a class="color-black px-55 py-5" href="#">SHOP</a>
          </li>
        </ul>
      </div>
    </div>
  </header>
  <main>

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
  padding-top: 55px;
  padding-bottom: 55px;
}

.py-5 {
  padding-left: 5px;
  padding-right: 5px;
}

.bgc-black {
  background-color: black;
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
</style>