
<script>
export default {
    name: 'AppLinks',
    data() {
        return {
            links: [
                {
                    text: 'DIGITAL COMICS',
                    img: '../img/aquietplace.jpeg'

                },
                {
                    text: 'DC MERCHANDISE',
                    img: '../img/aquietplace.jpeg'

                },
                {
                    text: 'SUBSCRIPTION',
                    img: '../img/aquietplace.jpeg'

                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    img: '../img/aquietplace.jpeg'

                },
                {
                    text: 'DC POWER VISA',
                    img: '../img/aquietplace.jpeg'

                }
            ]

        }

    }


}

</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col" v-for="item in links">
                <span>{{ item.img }} {{ item.text }}</span>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
.container {
    background-color: rgb(165, 167, 33);
}
</style>