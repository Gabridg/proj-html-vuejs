<template>
    <div id="bott-footer">
        <div class="container h-100">
            <div class="d-flex h-100">
                <div class="copyright">
                    @ Copyright 2012-2020 | Avada Theme by <a href="#">ThemeFusion</a> | All Rights
                    Reserved | Powered by <a href="#">WordPress</a>
                </div>
                <div class="social-link">
                    <i class="fa-brands fa-facebook-f fa-2x"></i>
                    <i class="fa-brands fa-twitter fa-2x"></i>
                    <i class="fa-brands fa-youtube"></i>
                    <i class="fa-brands fa-instagram fa-2x"></i>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "BottomFooter",
}
</script>

<style lang="scss" scoped>
#bott-footer {
    background-color: var(--black);
    font-size: 12px;
    height: 100px;

    .d-flex {
        justify-content: space-between;
        align-items: center;
    }

    a {
        color: var(--green);

    }

    .fa-brands {
        font-size: 15px;
        color: var(--white);
        margin-right: 20px;
    }
}
</style>