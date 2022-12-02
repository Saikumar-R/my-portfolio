<template>
    <div class="userDetails">
        <div class="userIcon">
            <img src="../../assets/new.jpg" alt="" srcset="" width="50px" height="50px">
        </div>
        <div class="name-and-role">
            <h2>Saikumar Raghavapuram</h2>
            <h4>Front-end Developer</h4>
        </div>
    </div>
</template>

<script>
    export default {
        name:"UserDetails",
    }
</script>

<style lang="scss" scoped>
    .userDetails{
        margin-top: 15px;
        display: flex;
        .userIcon > img{
            height: 69px;
            width: 65px;
            border-radius: 59px;
            margin-right: 20px;
        }
    }
</style>