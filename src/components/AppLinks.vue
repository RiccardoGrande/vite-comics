
<script>
export default {
    name: 'AppLinks',
    data() {
        return {
            links: [
                {
                    text: 'DIGITAL COMICS',
                    img: './assets/img/buy-comics-digital-comics.png'

                },
                {
                    text: 'DC MERCHANDISE'

                },
                {
                    text: 'SUBSCRIPTION'

                },
                {
                    text: 'COMIC SHOP LOCATOR'

                },
                {
                    text: 'DC POWER VISA'

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