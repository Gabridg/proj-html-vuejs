<template>
    <div id="info-footer">
        <div class="container">
            <div class="row">
                <div class="logo col-3">
                    <img src="../assets/img/avada-drivers-logo-1x.png" alt="logo Avada">
                    <p>
                        Avada Driving School is the right choice for experienced drivers looking for refresher course,
                        or
                        the brand new driver wanting to pass first time.
                    </p>
                </div>
                <div class="contact-details col-3">
                    <h2>CONTACT DETAILS</h2>
                    <ul>
                        <li><i class="fa-solid fa-house"></i>
                            <span>
                                12345 North Main Street, New York, NY 555555
                            </span>
                        </li>
                        <li><i class="fa-solid fa-phone-flip"></i> 1.800.555.6789</li>
                        <li><i class="fa-solid fa-envelope"></i> info@your-domain.com</li>
                        <li><i class="fa-solid fa-link"></i> Theme-Fusion.com</li>
                    </ul>
                </div>
                <div class="courses-details col-3">
                    <h2>COURSES</h2>
                    <ul>
                        <li><i class="fa-solid fa-arrow-right"></i><a href="#">Pass Plus</a></li>
                        <li><i class="fa-solid fa-arrow-right"></i><a href="#">Intensive Course</a></li>
                        <li><i class="fa-solid fa-arrow-right"></i><a href="#">Automatic</a></li>
                        <li><i class="fa-solid fa-arrow-right"></i><a href="#">Instructor Training</a></li>
                    </ul>
                </div>
                <div class="rate-button col-3 text-center">
                    <img src="../assets/img/footer-ad-grid.png" alt="" class="img-fluid">
                    <a href="#" class="btn btn-primary rounded-pill mt-3 mb-5">BOOK NOW</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "TopFooter",
}
</script>

<style lang="scss" scoped>
#info-footer {
    background-image: url("../assets/img/footer-background-color.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.row {
    padding-top: 80px;
}

.logo {

    p {
        margin-top: 20px;
        color: var(--lightgrey);
        font-size: 12px;
        line-height: 30px;
    }
}

.contact-details {
    text-align: left;
    color: var(--lightgrey);

    h2 {
        font-size: 18px;
        font-weight: bold;
    }

    ul li {
        display: flex;
        align-items: baseline;
        margin-left: -25px;
        padding: 5px;
    }

    .fa-solid {
        margin-right: 15px;
    }
}

.courses-details {
    h2 {
        font-size: 18px;
        font-weight: bold;
    }

    ul li {
        display: flex;
        align-items: baseline;
        margin-left: -25px;
        padding: 5px;
    }

    .fa-solid {
        display: block;
        width: 20px;
        height: 20px;
        border-radius: 50%;
        margin-right: 15px;
        border: 3px solid var(--secondarygrey);
        color: var(--secondarygrey);
        font-size: 15px;
    }

}
</style>