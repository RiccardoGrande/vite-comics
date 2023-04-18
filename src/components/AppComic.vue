<script>
export default {
    name: 'AppComic',
    props: {
        comic: Object
    }

}
</script>


<template>
    <div class="col">
        <div class="comic">
            <img class="img-fluid" :src="comic.thumb" alt="">
            <h5>{{ comic.series }}</h5>
        </div>

    </div>
</template>



<style lang="scss" scoped>
img {
    aspect-ratio: 1/1;
}

h5 {
    color: #fff;
}
</style>