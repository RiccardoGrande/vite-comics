
<script>
import comics from '../comics.js'
export default {
    name: 'AppContent',
    data() {
        return {
            comics,


        }

    }


}

</script>

<template>
    <div class="jumbotron">

    </div>
    <section class="background">
        <div class="container">
            <h3>Current Series</h3>
            <div class="row row-cols-1 row-cols-sm-2 row-cols-3 row-cols-xxl-6">
                <AppComic :comic="comic" v-for="comic in comics"></AppComic>

            </div>
        </div>

    </section>
</template>



<style lang="scss" scoped>
.jumbotron {
    height: 400px;
    background-image: url('../assets/img/jumbotron.jpg');
}

.background {
    background-color: rgb(0, 0, 0);

}

.container {



    h3 {
        color: #ffff;
    }
}
</style>