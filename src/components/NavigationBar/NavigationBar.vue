<template>
    <div class="wrapper">
       <div class="container">
            <UserDetails />
            <NavigationTabs />
       </div>
       <div class="profession">
            <h2>Systems Engineer</h2>
            <h4>Tata Consultancy Services, Hyderabad</h4>
       </div>
    </div>
</template>

<script>
import UserDetails from './UserDetails.vue'
import NavigationTabs from './NavigationTabs.vue'
    export default {
        name:"NavigationBar",
        components:{
            UserDetails,
            NavigationTabs
        }
    }
</script>

<style lang="scss" scoped>
    .wrapper{
        h2,h4{
            color: rgb(249, 249, 249);
        }
        background-color: #2397a5;
        padding: 0 85px;
        .container{
            display: flex;
            justify-content: space-between;
        }
        .profession{
            text-align: center;
            padding: 20px 0px 5px 0px;
            h2{
                margin-bottom: 5px;
            }
        }
    }
</style>