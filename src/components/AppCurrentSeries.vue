<script>

export default {
    name: "Current Series",
    props: {
        books: Array,
    }
}
</script>

<template>
    <div class="container">
        <div id="current-series">
            <h1 class="flex">current series</h1>
        </div>
        <ul class="card-col">
            <li class="card" v-for="book in books">
                <figure>
                    <img :src="book.thumb" :alt="book.series">
                </figure>
                <h5>
                    <a href="book.thumb">{{ book.series }}</a>
                </h5>
            </li>
        </ul>
        <div class="flex center">
            <a class="btn" href="#">load more</a>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    position: relative;
    padding: 1.2rem 0;
}

#current-series {
    position: absolute;
    top: -20px;
    left: 0;

    display: inline-block;
    background-color: dodgerblue;
    padding: 10px 20px;

    h1 {
        color: white;
        text-transform: uppercase;
        font-size: 1.2rem;
        font-weight: 700;
    }

}

.card-col {
    display: flex;
    flex-wrap: wrap;
}

.card {
    padding: 1rem 0.5rem;
    height: auto;
    flex-basis: calc(100% / 6);

    figure {
        width: 175px;
        height: 175px;
        overflow: hidden;
        position: relative;
        text-align: center;

        img {
            position: relative;
            top: 75%;
            left: 50%;
            translate: -50% -50%;

            height: 150%;
            width: auto;
        }
    }

    h5 {
        margin-top: 10px;
        padding-left: 2px;
    }
}

a.btn {
    align-self: center;
    padding: 10px 30px;
    margin: 1rem;

    background-color: dodgerblue;

    text-transform: uppercase;
    font-size: 0.7rem;
    font-weight: 700;
    color: white;
}
</style>
