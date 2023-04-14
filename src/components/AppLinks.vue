
<script>
export default {
    name: 'AppLinks',
    data() {
        return {
            links: [
                {
                    text: 'DIGITAL COMICS',
                    img: '/src/assets/img/aquietplace.jpeg'

                },
                {
                    text: 'DC MERCHANDISE',
                    img: '/src/assets/img/aquietplace.jpeg'

                },
                {
                    text: 'SUBSCRIPTION',
                    img: '/src/assets/img/aquietplace.jpeg'

                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    img: '/src/assets/img/aquietplace.jpeg'

                },
                {
                    text: 'DC POWER VISA',
                    img: '/src/assets/img/aquietplace.jpeg'

                }
            ]

        }

    }


}

</script>

<template>
    <div class="background">
        <div class="container">
            <div class="row">
                <div class="col" v-for="item in links">
                    <img :src="item.img">
                    <span>{{ item.text }}</span>

                </div>
            </div>
        </div>

    </div>
</template>



<style lang="scss" scoped>
.background {
    background-color: rgb(5, 80, 255);

}

.container {
    padding: 1rem;


    img {
        height: 60px;
        padding: 10px;
    }

    span {
        font-size: 14px;
        color: white;
    }
}
</style>