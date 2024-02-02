<script>

export default {
    name: "Header",
    data: () => ({
        navs: [
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
        ]
    })
}
</script>

<template>
    <header>
        <div class="container flex justify-header">

            <figure>
                <img src="../assets/img/dc-logo.png" alt="DC Logo">
            </figure>
            <nav class="flex center">
                <ul class="flex">
                    <li class="flex center list-setup" v-for="nav in navs">
                        <a class="link-setup flex center" href="{{ nav.url }}">
                            {{ nav.text }}
                        </a>
                    </li>
                </ul>
            </nav>

        </div>
    </header>
</template>

<style lang="scss" scoped>
header {
    height: 100px;
}

figure {
    height: 75px;
    align-self: center;
}

img {
    height: 100%;
    width: auto;
}

.justify-header {
    justify-content: space-between;
}

.link-setup {
    text-decoration: none;
    text-transform: uppercase;
    font-weight: 700;
    font-size: 0.8rem;

    color: rgba(48, 48, 48, 0.788);

    margin: 0 0.75rem;
}

ul,
a {
    height: 100px;
    border-bottom: 5px solid transparent;
    transition: border-bottom 0.3s;

}

a:hover,
a:active {

    border-bottom: 5px solid dodgerblue;
    color: dodgerblue;
}


.list-setup {
    list-style-type: none;
}
</style>
