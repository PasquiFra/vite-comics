<script>

export default {
    name: "Footer center",
    data: () => ({
        comixLinks: [
            {
                text: 'characters',
                url: '#'
            },
            {
                text: 'comics',
                url: '#'
            },
            {
                text: 'movies',
                url: '#'
            },
            {
                text: 'TV',
                url: '#'
            },
            {
                text: 'games',
                url: '#'
            },
            {
                text: 'videos',
                url: '#'
            },
            {
                text: 'news',
                url: '#'
            },
        ],
        shopLinks: [
            {
                text: 'shop DC',
                url: '#'
            },
            {
                text: 'shop DC collectibles',
                url: '#'
            },
        ],
        DCLinks: [
            {
                text: 'terms of use',
                url: '#'
            },
            {
                text: 'privacy policy (new)',
                url: '#'
            },
            {
                text: 'ad choices',
                url: '#'
            },
            {
                text: 'advertising',
                url: '#'
            },
            {
                text: 'jobs',
                url: '#'
            },
            {
                text: 'subscriptions',
                url: '#'
            },
            {
                text: 'talent workshops',
                url: '#'
            },
            {
                text: 'CPSC certificates',
                url: '#'
            },
            {
                text: 'ratings',
                url: '#'
            },
            {
                text: 'shop help',
                url: '#'
            },
            {
                text: 'contact us',
                url: '#'
            },
        ],
        sitesLinks: [
            {
                text: 'DC',
                url: '#'
            },
            {
                text: 'MAD magazine',
                url: '#'
            },
            {
                text: 'DC kids',
                url: '#'
            },
            {
                text: 'DC universe',
                url: '#'
            },
            {
                text: 'DC power visa',
                url: '#'
            },
        ],
    })
}
</script>

<template>
    <footer id="footer-center">
        <div class="container flex">

            <nav class="flex ">
                <h3>dc comics</h3>
                <ul>
                    <li v-for="link in comixLinks"><a :href="link.url">{{ link.text }}</a></li>
                </ul>
            </nav>

            <nav class="flex">
                <h3>shop</h3>
                <ul>
                    <li v-for="link in shopLinks"><a :href="link.url">{{ link.text }}</a></li>
                </ul>
            </nav>

            <nav class="flex">
                <h3>dc</h3>
                <ul>
                    <li v-for="link in DCLinks"><a :href="link.url">{{ link.text }}</a></li>
                </ul>
            </nav>

            <nav class="flex">
                <h3>sites</h3>
                <ul>
                    <li v-for="link in sitesLinks"><a :href="link.url">{{ link.text }}</a></li>
                </ul>
            </nav>

            <figure>
                <img src="../assets/img/dc-logo-bg.png" alt="DC-Logo">
            </figure>

        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;

    padding: 2rem 0;
    height: 400px;

    overflow: hidden;
}

nav {
    width: 200px;
    margin: 1rem 0;
}

.flex {
    flex-wrap: wrap;
    flex-direction: column;
    align-content: flex-start;
}

.container {
    height: 100%;
}

h3 {
    color: white;
    text-transform: uppercase;
    padding-bottom: 0.6rem;
}

li {
    text-transform: capitalize;
    list-style-type: none;
    padding: 2px 0;
}

a {
    text-decoration: none;
    text-transform: capitalize;

    color: rgba(169, 169, 169, 0.705);
    font-size: 0.8rem;
    font-weight: 500;


    &:hover {
        color: dodgerblue;
    }
}


figure {
    height: 100%;
    position: relative;
}

img {
    position: relative;
    top: 50%;
    left: 50%;
    translate: -50% -50%;

    width: 80%;
}
</style>
