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
                        <div class="circle">
                            <div class="almost-fill">
                                <div class="rate">
                                    95%
                                </div>
                            </div>
                        </div>
                        <h4>PASS RATE</h4>
                    </div>
                    <div class="rate-card">
                        <div class="circle">
                            <div class="fill">
                                <div class="rate">
                                    100%
                                </div>
                            </div>
                        </div>
                        <h4>REFERRAL RATE</h4>
                    </div>
                    <div class="rate-card">
                        <div class="circle">
                            <div class="empty">
                                <div class="rate">
                                    0%
                                </div>
                            </div>
                        </div>
                        <h4>ACCIDENT RATE</h4>
                    </div>
                </div>
            </div>
        </section>
        <section id="instructors">
            <div class="container">
                <h2>Your Instructors</h2>
                <div class="row">
                    <p class="col-8">
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugiat earum obcaecati quidem hic
                        dolorum,
                        distinctio, laboriosam quas eligendi eos eveniet excepturi voluptatem neque!
                    </p>
                    <a href="#" class="btn btn-primary rounded-pill col-4">MORE ABOUT US</a>
                </div>
                <div id="card-inst">

                    <div class="instructor-card">
                        <img src="../assets/img/instructor-mikehart.jpg" alt="Mike Hart" class="img-fluid">
                        <h4>Mike Hart</h4>
                        <div class="social">
                            <i class="fa-brands fa-facebook-f fa-2x"></i>
                            <i class="fa-brands fa-twitter fa-2x"></i>
                            <i class="fa-brands fa-instagram fa-2x"></i>
                        </div>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit</span>
                    </div>
                    <div class="instructor-card">
                        <img src="../assets/img/instructor-johnsmith.jpg" alt="John Smith" class="img-fluid">
                        <h4>John Smith</h4>
                        <div class="social">
                            <i class="fa-brands fa-facebook-f fa-2x"></i>
                            <i class="fa-brands fa-twitter fa-2x"></i>
                            <i class="fa-brands fa-instagram fa-2x"></i>
                        </div>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit</span>
                    </div>
                    <div class="instructor-card">
                        <img src="../assets/img/instructor-angelahart.jpg" alt="Angela Hart" class="img-fluid">
                        <h4>Angela Hart</h4>
                        <div class="social">
                            <i class="fa-brands fa-facebook-f fa-2x"></i>
                            <i class="fa-brands fa-twitter fa-2x"></i>
                            <i class="fa-brands fa-instagram fa-2x"></i>
                        </div>
                        <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit</span>
                    </div>
                </div>
            </div>
        </section>
        <section id="testimonials">
            <div class="container">
                <h2>Testimonials</h2>
                <span>Here's what our happy drivers had to say about our services:</span>
                <TestimonialCard>
                </TestimonialCard>
            </div>
        </section>
        <section id="latest-news">
            <div class="container">
                <div class="news-card text-center">
                    <h2 class="text-center">Latest News</h2>
                    <div class="d-flex justify-content-between">

                        <div class="text-center mt-3 card-int">
                            <img src="../assets/img/blog-choosecar-320x202.jpg" alt="">
                            <h4>What Car to Start With?</h4>
                            <span class="data">February 7th, 2019 | <a href="">0 Comments</a></span>
                            <span>Lorem impsum dolor sit amet, consectetur adipising</span>
                        </div>
                        <div class="text-center mt-3 card-int">
                            <img src="../assets/img/blogpost-10and2-320x202.jpg" alt="">
                            <h4>Avada drivin School Expanding</h4>
                            <span class="data">February 7th, 2019 | <a href="">0 Comments</a></span>
                            <span>Lorem impsum dolor sit amet, consectetur adipising</span>
                        </div>
                    </div>
                    <a href="#" class="btn btn-primary rounded-pill mt-4">MORE FROM THE BLOG</a>
                </div>
                <img src="../assets/img/latestnews-bottom-800x70.png" alt="" class="footer-latest-news">
            </div>
        </section>
        <section id="newsletter">
            <div class="container">
                <h2></h2>
                <div class="form-newsletter">
                    <input type="text" class="form-control">
                    <a href="#" class="btn btn-primary rounded-pill">SUBSCRIBE</a>
                    <p>(We do not share yopur data with anybody, and only use it for its intended purpose)</p>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
import FormsCard from './FormsCard.vue';
import TestimonialCard from './TestimonialCard.vue';
export default {
    name: "TheMain",
    components: { FormsCard, TestimonialCard },

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
    background-image: url("../assets/img/promise-background.jpg");
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

    .circle {
        width: 250px;
        height: 250px;
        border-radius: 50%;
        background-color: var(--green);
        margin: 50px auto;
    }

    .almost-fill {
        width: 250px;
        height: 250px;
        position: relative;
        background: conic-gradient(var(--green) 342deg, var(--white) 0deg);
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;

    }

    .fill {
        width: 250px;
        height: 250px;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .empty {
        width: 250px;
        height: 250px;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        background: conic-gradient(var(--green) 10deg, var(--white) 0deg);
        border: 1px solid var(--green);
        border-radius: 50%;
    }

    .empty::before {
        content: "";
        position: absolute;
        height: 210px;
        width: 210px;
        border-radius: 50%;
        background-color: var(--white);
        border: 1px solid var(--green);
    }

    .fill::before {
        content: "";
        position: absolute;
        height: 210px;
        width: 210px;
        border-radius: 50%;
        background-color: var(--white);
    }

    .almost-fill::before {
        content: "";
        position: absolute;
        height: 210px;
        width: 210px;
        border-radius: 50%;
        background-color: var(--white);
    }

    .rate {
        line-height: 185px;
        text-align: center;
        font-weight: 700;
        font-size: 32px;
        position: relative;
    }

    h4 {
        color: var(--lightgrey);
        font-weight: 600;
        font-size: 18px;
        margin: 60px auto;
        transform: rotate(0deg);
    }

}

#instructors {
    h2 {
        font-size: 45px;
        font-weight: 600;
        color: var(--grey);
    }

    p {
        color: var(--secondarygrey);
        line-height: 45px;
        font-weight: 400;
        font-size: 20px;
        margin-top: 50px;
    }

    a {
        margin-top: 15px;
        height: 40px;
        font-size: 15px;
        font-weight: 600;
    }

    #card-inst {
        display: flex;
    }

    .instructor-card {
        max-width: 450px;
        height: 500px;
        border-radius: 20px;
        margin: 50px;
        text-align: center;
        border-top: 5px solid var(--green);
        border-radius: 20px;
        box-shadow: 5px 5px 25px var(--grey);
        position: relative;
        bottom: -100px;
        left: 0;
        background-color: var(--white);

        img {
            width: 250px;
            margin: 50px auto;
        }

        span {
            line-height: 35px;
            color: var(--grey);
            font-weight: 600;
        }
    }

    .social {
        color: var(--grey);
        margin: 25px;
        font-size: 12px;

        .fa-brands {
            margin: 10px;
        }
    }
}

#testimonials {
    text-align: center;

    h2 {
        color: var(--grey);
        font-size: 35px;
        font-weight: bold;
    }

    span {
        color: var(--secondarygrey);
        font-size: 20px;
    }
}

#latest-news {
    background-image: url("../assets/img/latestnews-background.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 700px;

    .news-card {
        background-color: var(--white);
        max-width: 850px;
        margin: 0 auto;
        height: 500px;
        border-top: 4px solid var(--secondarygrey);
        border-top-left-radius: 20px;
        border-top-right-radius: 20px;
        position: relative;
        top: -50px;
        left: 0;

        img {
            height: 200px;
            width: 300px;
            padding: 10px
        }

        .card-int {
            margin-right: 30px;

            h4 {
                color: var(--green);
                font-weight: 600;
            }

            .data {
                display: block;
                font-size: 12px;

                a {
                    color: var(--secondarygrey);
                    text-decoration: none;
                }
            }

            span {
                color: var(--grey);
                font-size: 18px;
            }
        }
    }

    .footer-latest-news {
        position: relative;
        top: -50px;
        left: 224px;
        width: 850px;
    }

}

#newsletter {
    background-image: url("../assets/img/newsletter_background.jpg");
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;
    height: 300px;
    text-align: center;
    margin-top: -20px;

    .form-newsletter {
        padding-top: 50px;
    }

    .form-newsletter input {
        max-width: 400px;
        margin: 0 auto;
        padding: 10px;
    }

    .form-newsletter a {
        margin-top: 50px;
        padding: 5px 160px;
    }

    .form-newsletter p {
        margin-top: 25px;
    }
}
</style>
