<template>
    <div class="forms col-6">
        <h2 class="m-3">First Lesson Free!</h2>
        <span>When you make a block booking with us your first lesson is included free.</span>
        <div class="input-control">
            <input type="text" class="form-control p-3" placeholder="Your Name*" v-model.trim="userName">
            <input type="email" class="form-control p-3" placeholder="Email*" v-model.trim="email">
            <input type="text" class="form-control p-3" placeholder="Telephone" v-model.trim="telephone">
            <input type="text" class="form-control p-3" placeholder="Location" v-model.trim="location">
            <a href="#" class="btn btn-primary mt-4" @click="emitSave">REQUEST A CALLBACK</a>
        </div>
    </div>
</template>

<script>
export default {
    name: "FormsCard",
    data() {
        return {
            userName: '',
            email: '',
            telephone: '',
            location: '',
        }
    },
    methods: {
        emitSave() {
            this.$emit('userInfo', this.userName, this.email, this.telephone, this.location)
        }
    }
}
</script>

<style lang="scss">
.forms {
    text-align: center;
    background-color: var(--white);
    box-shadow: 5px 5px 25px var(--grey);
    position: relative;
    top: -150px;
    height: 600px;
    border-radius: 10px;

    h2 {
        color: var(--green);
    }

    span {
        color: var(--secondarygrey);
        margin: 20px 10px;
        font-size: 20px;
    }

    input {
        background-color: var(--lightgrey);
        margin: 20px 10px;
    }

    input::placeholder {
        color: var(--secondarygrey);
    }

    .input-control {
        margin: 32px;
    }
}
</style>