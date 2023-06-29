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
        <img src="./assets/img/dc-logo.png" alt="dc-logo">
      </figure>
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

.container {
  margin: 0 auto;
  max-width: 1200px;
}

.h-30 {
  height: 30px;
}

.bgc-black {
  background-color: black;
}

.header-nav {
  display: flex;
  justify-content: space-between;
}
</style>