<script>

export default {
    name: "Footer bottom"
}
</script>

<template>
    <footer id="footer-bottom">
        <div class="container flex justify-between">
            <nav class="flex center">
                <div class="sign-up">
                    <a>SIGN-UP NOW!</a>
                </div>
            </nav>

            <nav class="flex center">
                <ul class="flex center">
                    <li>
                        <h3>FOLLOW US</h3>
                    </li>
                    <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a></li>
                </ul>
            </nav>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer {
    height: 100px;
    background-color: rgb(56, 56, 56);
}

nav {
    height: 100px;
}

h3 {
    color: dodgerblue;
    font-size: 1rem;
}

li {
    list-style: none;
    margin: 0 0.5rem;
}

.sign-up {
    border: 3px solid dodgerblue;
    color: white;
    font-weight: 600;

    padding: 0.8rem;
}
</style>
