<template>
    <div>
        <section id="alert-info">
            <div class="container">
                <div class="d-flex justify-content-between align-items-center">
                    <span>We have a 95% Successful Pass Rate!</span>
                    <span>
                        <i class="fa-solid fa-phone-flip pe-2"></i>
                        give us a call to book your tuition!
                        1-800-555-555
                    </span>
                </div>
            </div>
        </section>
        <section class="navbar">
            <div class="container">
                <div class="d-flex justify-content-between align-items-center w-100">
                    <div>
                        <img src="../assets/img/avada-drivers-logo-1x.png" alt="avada logo">
                    </div>
                    <div>
                        <ul class="d-flex align-items-center">
                            <li><a href="#">{{ home }}</a></li>
                            <li><a href="#">{{ about }}</a></li>
                            <li><a href="#">{{ prices }}</a></li>
                            <li><a href="#">{{ courses }}</a></li>
                            <li><a href="#">{{ locations }}</a></li>
                            <li><a href="#">{{ blog }}</a></li>
                            <li><a href="#" class="btn btn-primary rounded-pill">BOOK NOW</a></li>

                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section id="jumbotron">
            <div class="container jumbo">
                <h1 class="fw-bold">Drive with Avada</h1>
                <span class="fs-4">We offer the finest driving tuition money can buy</span>
            </div>
        </section>
    </div>
</template>


<script>
export default {
    name: 'TheHeader',
    props: {
        home: String,
        about: String,
        prices: String,
        courses: String,
        locations: String,
        blog: String
    }
}
</script>


<style lang="scss">
@import '../assets/scss/style.scss';

#alert-info {
    background-color: var(--grey);
    color: var(--lightgrey);
    padding: 15px;

    span {
        font-size: 12px;
    }
}

ul {
    list-style: none;
    margin-bottom: 0;

    li {
        padding: 15px 30px;
    }

    a {
        text-decoration: none;
        color: var(--white);
        font-weight: bold;
    }

    a:hover {
        color: var(--green);
        border-bottom: 2px solid var(--green);
    }
}

.btn-primary {
    background-color: var(--lightgreen);
    border-color: var(--lightgreen);
}

.btn-primary:hover {
    background-color: var(--green);
    border-color: var(--green);
    font-size: 20px;
    font-weight: bold;
}

.navbar {
    background-color: #0005;
    position: absolute;
    width: 100%;
    padding: 20px 0;
}

#jumbotron {
    background-image: url("../assets/img/homepage-hero-background.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 700px;
    color: var(--white);
}

.jumbo {
    padding-top: 15%;

    h1 {
        font-size: 60px;
    }

    span {
        font-size: 40px;
    }
}
</style>