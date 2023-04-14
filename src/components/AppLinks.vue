
<script>
export default {
    name: 'AppLinks',
    data() {
        return {
            links: [
                {
                    text: 'DIGITAL COMICS',
                    img: 'https://i0.wp.com/www.comicon.com/wp-content/uploads/2020/04/BATMAN-GOTHAM-NIGHTS-1_5e9dd8c96bfe20.09849239.jpg?resize=390%2C600'

                },
                {
                    text: 'DC MERCHANDISE',
                    img: 'https://mlpnk72yciwc.i.optimole.com/cqhiHLc.IIZS~2ef73/w:auto/h:auto/q:75/https://bleedingcool.com/wp-content/uploads/2020/06/Page-1.jpg'

                },
                {
                    text: 'SUBSCRIPTION',
                    img: 'https://mlpnk72yciwc.i.optimole.com/cqhiHLc.IIZS~2ef73/w:auto/h:auto/q:75/https://bleedingcool.com/wp-content/uploads/2020/06/Page-1.jpg'

                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    img: 'https://mlpnk72yciwc.i.optimole.com/cqhiHLc.IIZS~2ef73/w:auto/h:auto/q:75/https://bleedingcool.com/wp-content/uploads/2020/06/Page-1.jpg'

                },
                {
                    text: 'DC POWER VISA',
                    img: 'https://mlpnk72yciwc.i.optimole.com/cqhiHLc.IIZS~2ef73/w:auto/h:auto/q:75/https://bleedingcool.com/wp-content/uploads/2020/06/Page-1.jpg'

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