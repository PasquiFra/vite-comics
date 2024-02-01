<script>

export default {
    name: "Footer center"
}
</script>

<template>
    <footer id="footer-center">
        <div class="container flex">

            <nav class="flex ">
                <h3>dc comics</h3>
                <ul>
                    <li><a href="#">characters</a></li>
                    <li><a href="#">comics</a></li>
                    <li><a href="#">movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">games</a></li>
                    <li><a href="#">videos</a></li>
                    <li><a href="#">news</a></li>
                </ul>
            </nav>

            <nav class="flex">
                <h3>shop</h3>
                <ul>
                    <li><a href="#">shop DC</a></li>
                    <li><a href="#">shop DC collectibles</a></li>
                </ul>
            </nav>

            <nav class="flex">
                <h3>dc</h3>
                <ul>
                    <li><a href="#">terms of use</a></li>
                    <li><a href="#">privacy policy (new)</a></li>
                    <li><a href="#">ad choices</a></li>
                    <li><a href="#">advertising</a></li>
                    <li><a href="#">jobs</a></li>
                    <li><a href="#">subscriptions</a></li>
                    <li><a href="#">talent workshops</a></li>
                    <li><a href="#">CPSC certificates</a></li>
                    <li><a href="#">retings</a></li>
                    <li><a href="#">shop help</a></li>
                    <li><a href="#">contact us</a></li>
                </ul>
            </nav>

            <nav class="flex">
                <h3>sites</h3>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD magazine</a></li>
                    <li><a href="#">DC kids</a></li>
                    <li><a href="#">DC universe</a></li>
                    <li><a href="#">DC power visa</a></li>
                </ul>
            </nav>
            <figure>
                <img src="../assets/img/dc-logo-bg.png" alt="DC-Logo">
            </figure>
        </div>
    </footer>
</template>

<style scoped>
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
    list-style-type: none
}

a {
    text-decoration: none;
    color: rgba(169, 169, 169, 0.705);
    font-size: 0.8rem;
    font-weight: 500;
}

a:hover {
    color: dodgerblue;
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
