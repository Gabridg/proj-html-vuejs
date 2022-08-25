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
                <div class="row">
                    <div class="info-courses col-6 text-center">
                        <h2 class="m-4">Courses</h2>
                        <p class="m-3">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic aliquam itaque accusamus iusto
                            expedita quam illum ratione autem, est repellendus reiciendis omnis, nobis praesentium id
                            quo aliquid veritatis delectus sequi!
                        </p>
                        <a href="#" class="btn btn-primary m-3 rounded-pill">COURSE INFORMATION</a>

                    </div>
                    <div class="school-info col-6 d-flex align-items-center">
                        <div class="course-card">
                            <img src="../assets/img/courses-passplus.jpg" alt="" class="img-fluid">
                            <div class="course-txt">

                                <h4>Pass Plus</h4>
                                <a href="#" class="btn btn-secondary rounded-pill">LEARN MORE</a>
                            </div>
                        </div>
                        <div class="course-card">
                            <img src="../assets/img/course-intensive.jpg" alt="" class="img-fluid">
                            <div class="course-txt">

                                <h4>Intensive Course</h4>
                                <a href="#" class="btn btn-secondary rounded-pill">LEARN MORE</a>
                            </div>
                        </div>
                        <div class="course-card">
                            <img src="../assets/img/courses-instructor.jpg" alt="" class="img-fluid">
                            <div class="course-txt">
                                <h4>Instructors</h4>
                                <a href="#" class="btn btn-secondary rounded-pill">LEARN MORE</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="perc-rate">
            <div class="container">
                <div class="d-flex">
                    <div class="rate-card">
                        <div class="rate">
                            95%
                        </div>
                        <h4>PASS RATE</h4>
                    </div>
                    <div class="rate-card">
                        <div class="rate">
                            100%
                        </div>
                        <h4>REFERRAL RATE</h4>
                    </div>
                    <div class="rate-card">
                        <div class="rate">
                            0%
                        </div>
                        <h4>ACCIDENT RATE</h4>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
import FormsCard from './FormsCard.vue';
export default {
    name: "TheMain",
    components: { FormsCard, },
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

#courses {
    background-image: url(../assets/img/promise-background.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

    .info-courses {
        height: 450px;
        border-radius: 20px;
        box-shadow: 5px 5px 25px var(--grey);
        width: 500px;
        position: relative;
        top: -30px;
        background-color: var(--white);

        h2 {
            font-size: 50px;
            font-weight: 600;
            color: var(--grey);
            padding: 20px;
        }

        p {
            font-weight: 400;
            color: var(--secondarygrey);
            padding: 25px;
            line-height: 35px;
            font-size: 15px;
        }

        a {
            color: var(--white);
            font-weight: bold;
            padding: 15px;
            margin-top: 20px;
        }


    }

    .school-info {
        width: 770px;
        margin-left: 50px;
    }

    .course-card {
        text-align: center;
        margin: 30px;

        .course-txt {
            margin-top: 30px;
            color: var(--grey);

            h4 {
                font-weight: 600;
            }

            a {
                background-color: transparent;
                border: 2px solid var(--grey);
                font-weight: 400;
                color: var(--grey);
                font-size: 13px;
            }
        }

    }

}

.rate-card {
    margin: 150px auto;
    width: 400px;
    height: 450px;
    text-align: center;
    border-top: 5px solid var(--green);
    border-radius: 20px;
    box-shadow: 5px 5px 25px var(--grey);

    .rate {
        width: 200px;
        height: 200px;
        border-radius: 50%;
        border: 8px solid var(--green);
        text-align: center;
        line-height: 200px;
        font-size: 50px;
        margin: 50px auto;
    }

    h4 {
        color: var(--lightgrey);
        font-weight: 600;
        font-size: 18px;
        margin: 60px;
    }
}
</style>