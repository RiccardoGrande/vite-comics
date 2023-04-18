<script>
export default {
    name: 'AppComic',
    props: {
        comic: object
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



<style lang="scss" scoped></style>