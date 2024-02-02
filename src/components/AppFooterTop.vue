<script>

export default {
    name: "Footer Top"
}
</script>

<template>
    <footer id="footer-top">
        <div class="container flex center">

            <ul class="flex">
                <li>
                    <a href="#">
                        <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
                        <span>digital comics</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="@/assets/img/buy-comics-merchandise.png" alt="">
                        <span>dc merchandise</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
                        <span>subscription</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
                        <span>comic shop locator</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="@/assets/img/buy-dc-power-visa.svg" alt="">
                        <span>dc power visa</span>
                    </a>
                </li>
            </ul>

        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer {
    background-color: dodgerblue;

    height: 125px;
}


ul {
    list-style-type: none;


    li {
        margin: 20px;

        a {
            height: 40px;
            display: flex;
            align-items: center;
        }

    }

    img {
        height: 100%;
    }

    span {
        text-transform: uppercase;
        color: white;
        font-size: 0.75rem;

        padding: 0 8px;
    }

}
</style>
