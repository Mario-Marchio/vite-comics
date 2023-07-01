<script>
export default {
    props: {
        cards: Array
    }
}
</script>

<template>
    <div class="container card-container">
        <div v-for="card in cards" :key="card.series" class="card">
            <img :src="card.thumb">
            <h3>{{ card.series }}</h3>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 2rem;
}

.card {
    flex-basis: calc(100% / 6);
    padding: 20px;

    img {
        height: 246px;

    }

    h3 {
        color: white;
    }
}
</style>