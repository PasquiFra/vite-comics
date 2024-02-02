<script>
import AppCurrentSeries from './AppCurrentSeries.vue'

export default {
    name: "Main",
    components: {
        AppCurrentSeries
    },
    props: {
        books: Array,
    }
}
</script>

<template>
    <main class="flex">
        <AppCurrentSeries :books="books" />
    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: rgb(31, 30, 30);
}
</style>
