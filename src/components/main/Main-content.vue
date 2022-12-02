<template>
    <div class="main-container">
        <MainImage />
        <MutableComponent />
    </div>
</template>

<script>
import MainImage from './Main-Image.vue'
import MutableComponent from './MutableComponet.vue'
    export default {
        name:"MainContent",
        components:{
            MainImage,
            MutableComponent
        }
    }
</script>

<style lang="scss" scoped>
    .main-container{
        padding: 20px 85px;
        display: flex;
        justify-content: space-between;
    }
</style>