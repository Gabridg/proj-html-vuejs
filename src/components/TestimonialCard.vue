<template>
    <div class="container">
        <div id="tetimonials" v-for="(testimonial, index) in testimonials" :key="testimonial.testName"
            :class="currentActiveIndex === index ? 'active' : 'pics'">
            <img :src="testimonial.image" alt="">
            <p>{{ testimonial.description }}</p>
            <span id="testimonial-name">{{ testimonial.testName }}</span>
            <div id="thumb" class="d-flex align-items-center justify-content-center mt-3">
                <i v-for="(testimonial, index) in testimonials" :key="testimonial.testName"
                    class="fa-solid fa-circle-dot" :class="{ 'active': currentActiveIndex === index }"
                    @click="currentActiveIndex = index"></i>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'TestimonialCard',
    data() {
        return {
            currentActiveIndex: 0,
            testimonials: [
                {
                    image: require('../assets/img/testimonial-sophia.png'),
                    description: 'lorem impsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.',
                    testName: 'Sophia Jones'
                },
                {
                    image: require('../assets/img/testimonial-grant.png'),
                    description: 'lorem impsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.',
                    testName: 'Grant Jones'
                },
                {
                    image: require('../assets/img/testimonial-harold.png'),
                    description: 'lorem impsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.',
                    testName: 'Harol Jones'
                },
                {
                    image: require('../assets/img/testimonial-kate.png'),
                    description: 'lorem impsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.',
                    testName: 'Kate Jones'
                },
                {
                    image: require('../assets/img/testimonial-kelly.png'),
                    description: 'lorem impsum dolor sit amet, consectetur adipiscing elit. Nunc ultrices auctor sapien id cursus. Aliquam maximus turpis in vehicula semper.',
                    testName: 'Kelly Jones'
                }
            ]
        }
    },
    computed: {
        isFirst() {
            return this.currentActiveIndex === 0
        },
        isLast() {
            return this.currentActiveIndex === this.testimonials.length - 1
        }
    },
    methods: {
        nextPic() {
            if (this.isLast) this.currentActiveIndex = 0;
            else this.currentActiveIndex++;
        },
        prevPic() {
            if (this.isFirst) this.currentActiveIndex = this.testimonials.length - 1;
            else this.currentActiveIndex--;
        }
    }
}
</script>

<style lang="scss">
#testimonials {
    padding-top: 150px;
    background-image: url("../assets/img/testimonial-background.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding-bottom: 100px;

    img {
        height: 150px;
        margin: 50px;
    }

    .pics {
        display: none;
    }

    .active {
        display: block;
    }

    #thumb .active {
        background-color: var(--secondarygrey);
        border-radius: 50%;
    }

    i {
        margin-right: 10px;
        cursor: pointer;
        color: var(--secondarygrey);
    }
}
</style>