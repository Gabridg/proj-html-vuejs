<template>
    <div class="main">
        <div class="container">
            <section class="behind-wheel mt-5 row">
                <div class="description col-6">
                    <h2>Get Behind The Wheel</h2>
                    <p>
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Possimus eius quia iure voluptate quo
                        cum
                        nisi minus dignissimos ratione aliquam.
                    </p>
                    <span>
                        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsam facere laudantium veritatis
                        accusantium quod hic, aut adipisci nulla at harum temporibus corrupti dolores esse voluptate
                        sint
                        tenetur sunt possimus rem?Lorem ipsum dolor sit amet consectetur, adipisicing elit. Consectetur,
                        reprehenderit id. Laborum, voluptates reiciendis ab sint, quaerat maxime magni ut ea nesciunt
                        quam
                        necessitatibus nisi nam. Molestias tempora eius nemo.
                    </span>
                </div>
                <FormsCard @userInfo="userLogin"></FormsCard>
            </section>
        </div>
        <section id="courses-head">
            <div class="container h-100">
                <div class="h-100 d-flex align-items-center justify-content-between">
                    <div>
                        <h2>Start Learning to Drive Today</h2>
                        <span>Give us a call to schedule your first driving lesson</span>
                    </div>
                    <div class="text-center">
                        <i class="fa-solid fa-phone-flip fa-2x"></i>
                        <span id="phone-number">1-800-555-555</span>
                    </div>
                </div>
            </div>
        </section>
        <section id="courses">
            <div class="container">
                <div class="info-courses">

                </div>
                <div class="school-info">

                </div>
            </div>
        </section>
    </div>
</template>

<script>
import FormsCard from './FormsCard.vue';
export default {
    name: "TheMain",
    components: { FormsCard },
    methods: {
        userLogin() {
            return alert('Hai effettuato il login!');
        }
    }
}
</script>

<style lang="scss">
.description {
    margin: 0 auto;

    h2 {
        font-size: 45px;
        color: var(--grey);
        font-weight: 600;
    }

    p {
        font-size: 25px;
        color: var(--secondarygrey);
        font-weight: 400;
        margin: 20px 0;
        line-height: 45px;
    }

    span {
        color: var(--secondarygrey);
    }
}

#courses-head {
    background-image: url("../assets/img/horizontal-cta-background.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 250px;
    color: var(--white);
    vertical-align: middle;

    h2 {
        font-size: 40px;
        font-weight: bold;
    }

    span {
        font-size: 25px;
        font-weight: bold;
    }

    #phone-number {
        font-size: 40px;
        font-weight: normal;
    }

    .fa-phone-flip {
        margin-right: 35px;
    }
}
</style>