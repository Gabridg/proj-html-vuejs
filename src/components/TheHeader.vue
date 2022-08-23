<template>
    <div>
        <section id="alert-info">
            <div class="container">
                <div class="d-flex justify-content-between align-items-center">
                    <span>We have a 95% Successful Pass Rate!</span>
                    <span>
                        <i class="fa-solid fa-phone-flip"></i>
                        give us a call to book your tuition!
                        1-800-555-555
                    </span>
                </div>
            </div>
        </section>
        <section class="navbar">
            <div class="container">
                <div class="d-flex">
                    <div>
                        <img src="../assets/img/avada-drivers-logo-1x.png" alt="avada logo">
                    </div>
                    <div>
                        <ul>
                            <li><a href="#">HOME</a></li>
                            <li><a href="#">ABOUT</a></li>
                            <li><a href="#">PRICES</a></li>
                            <li><a href="#">COURSES</a></li>
                            <li><a href="#">LOCATIONS</a></li>
                            <li><a href="#">BLOG</a></li>
                            <li><a href="#" class="btn btn-primary">BOOK NOW</a></li>

                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section id="jumbotron">
            <h1>Drive with Avada</h1>
            <span>We offer the finest driving tuition money can buy</span>
        </section>
    </div>
</template>


<script>
export default {
    name: 'TheHeader',
}
</script>


<style lang="scss">
@import '../assets/scss/style.scss';

#alert-info {
    background-color: var(--grey);
    color: var(--lightgrey)
}
</style>