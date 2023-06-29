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


}

</script>

<template>
    <header>
        <div class="h-40 bgc-black"></div>
        <div class="container header-nav">
            <figure>
                <img class="p-10" src="../assets/img/dc-logo.png" alt="dc-logo">
            </figure>
            <div class="r-header-nav">
                <ul class="d-flex">
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
</template>
<style>
.p-10 {
    padding: 10px;
}

.px-55 {
    padding: 55px 0;
}

.py-5 {
    padding: 0 5px;
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