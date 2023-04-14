<script>
export default {
    name: 'AppFooter',
    data() {
        return {
            footer: [{
                sign: 'SIGN-UP NOW!',
                text: 'FOLLOW US',



            }]

        }

    }


}

</script>

<template>
    <div class="background">
        <div class="container">
            <div class="row">
                <div class="col" v-for="item in footer">
                    <span class="signup">{{ item.sign }}</span>
                </div>
                <div class="col" v-for="item in footer">
                    <span>{{ item.text }}</span>
                    <span>{{ item.icon_2 }}</span>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
            </div>
        </div>

    </div>
</template>



<style lang="scss" scoped>
.background {
    background-color: rgb(51, 51, 51);
}

.container {


    .col {

        padding: 1rem;

        .signup {

            border: 2px blue solid;
            color: #ffff;

        }

        span {
            padding: 0.5rem;
            color: blue;

        }

        img {
            padding: 0.5rem;

        }
    }
}
</style>