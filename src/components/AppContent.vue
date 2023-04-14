
<script>
export default {
    name: 'AppContent',
    data() {
        return {
            content: [
                {
                    text: '<-- Content goes here -->'
                }]

        }

    }


}

</script>

<template>
    <div class="background">
        <div class="container">
            <div class="row">
                <div class="col" v-for="item in content">
                    <h1>{{ item.text }}</h1>
                </div>
            </div>
        </div>

    </div>
</template>



<style lang="scss" scoped>
.background {
    background-color: rgb(0, 0, 0);

}

.container {



    h1 {
        color: #ffff;
    }
}
</style>