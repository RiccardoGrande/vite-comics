<script>
export default {
    name: 'AppInfo',
    data() {
        return {
            info_1: [

                {
                    title: 'DC COMICS',
                    text_1: 'Characters',
                    text_2: 'Comics',
                    text_3: 'Movies',
                    text_4: 'TV',
                    text_5: 'Games',
                    text_6: 'Videos',
                    text_7: 'News'



                }
            ],
            info_2: [

                {
                    title: 'DC',
                    text_1: 'Therm of use',
                    text_2: 'Privacy policy (New)',
                    text_3: 'Ad choices',
                    text_4: 'Advertising',
                    text_5: 'Jobs',
                    text_6: 'Subscriptions',
                    text_7: 'Talent workshops',
                    text_8: 'CPSPC Certificates',
                    text_9: 'Ratings',
                    text_10: 'Shop help',
                    text_11: 'Contact us',



                }
            ],
            info_3: [

                {
                    title: 'SHOP',
                    text_1: 'DC',
                    text_2: 'MAD MAgazine',
                    text_3: 'DC kids',
                    text_4: 'DC Universe',
                    text_5: 'DC powervisa',




                }
            ],
            info_4: [

                {
                    title: 'DC COMICS',
                    text_1: 'SHOP DC',
                    text_2: 'SHOP DC COLLECTIBLES',




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
                <div class="col" v-for="item in info_1">
                    <h4>{{ item.title }}</h4>
                    <div>{{ item.text_1 }}</div>
                    <div>{{ item.text_2 }}</div>
                    <div>{{ item.text_3 }}</div>
                    <div>{{ item.text_4 }}</div>
                    <div>{{ item.text_5 }}</div>
                    <div>{{ item.text_6 }}</div>
                    <div>{{ item.text_7 }}</div>


                </div>
                <div class="col" v-for="item in info_2">
                    <h4>{{ item.title }}</h4>
                    <div>{{ item.text_1 }}</div>
                    <div>{{ item.text_2 }}</div>
                    <div>{{ item.text_3 }}</div>
                    <div>{{ item.text_4 }}</div>
                    <div>{{ item.text_5 }}</div>
                    <div>{{ item.text_6 }}</div>
                    <div>{{ item.text_7 }}</div>
                    <div>{{ item.text_8 }}</div>
                    <div>{{ item.text_9 }}</div>
                    <div>{{ item.text_10 }}</div>


                </div>
                <div class="col" v-for="item in info_3">
                    <h4>{{ item.title }}</h4>
                    <div>{{ item.text_1 }}</div>
                    <div>{{ item.text_2 }}</div>
                    <div>{{ item.text_3 }}</div>
                    <div>{{ item.text_4 }}</div>
                    <div>{{ item.text_5 }}</div>





                </div>
                <div class="col" v-for="item in info_4">
                    <h4>{{ item.title }}</h4>
                    <div>{{ item.text_1 }}</div>
                    <div>{{ item.text_2 }}</div>



                </div>

                <div class="col-8">


                </div>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>
.background {

    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;

}

.container {


    .row {
        flex-wrap: nowrap;

        .col-8 {
            background-image: url('../assets/img/dc-logo-bg.png');
            background-position: center;
            background-repeat: no-repeat;
        }

        h4 {
            color: #ffff
        }

        div {
            color: grey;
        }
    }
}
</style>