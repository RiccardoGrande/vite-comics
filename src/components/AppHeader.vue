
<script>
export default {
    name: 'AppHeader',
    data() {

        return {

            banner: [
                {
                    text: 'CHARACTERS',
                    src: '#'

                },
                {
                    text: 'COMICS',
                    src: '#'

                },
                {
                    text: 'MOVIES',
                    src: '#'

                },
                {
                    text: 'TV',
                    src: '#'

                },
                {
                    text: 'GAMES',
                    src: '#'

                },
                {
                    text: 'COLLECTIBLES',
                    src: '#'

                },
                {
                    text: 'VIDEOS',
                    src: '#'

                },
                {
                    text: 'FANS',
                    src: '#'

                },
                {
                    text: 'NEWS',
                    src: '#'

                },
                {
                    text: 'SHOP',
                    src: '#'

                }
            ]

        }

    }


}

</script>

<template>
    <header>
        <div class="container">
            <nav>
                <div class="row">
                    <div class="col-4 d-flex justify-content-center">
                        <img src="../assets/img/dc-logo.png" alt="dc_logo">

                    </div>
                    <div class="col-8 d-flex justify-content-center align-items-center">
                        <a :href="item.src" v-for="item in banner">{{ item.text }}</a>


                    </div>


                </div>

            </nav>

        </div>


    </header>
</template>



<style lang="scss" scoped>
header {

    text-align: center;
}




a {
    text-decoration: none;
    font-size: 12px;
    padding: 0 1rem;

}
</style>