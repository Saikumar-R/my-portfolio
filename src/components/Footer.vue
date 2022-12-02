<template>
    <div class="footer-wrapper">
         <h3>Click below Icons to follow me on Social Media</h3>
        <div class="social-media-logos">
            <a href=""><img src="../assets/facebook.png" alt="" srcset=""></a>
            <a href=""><img src="../assets/insta.png" alt="" srcset=""></a>
            <a href=""><img src="../assets/github.png" alt="" srcset=""></a>
            <a href=""><img src="../assets/twitter.png" alt="" srcset=""></a>
        </div>
    </div>
</template>

<script>
    export default {
        name:"FooterComponent"
    }
</script>

<style lang="scss" scoped>
    .footer-wrapper{
        background-color: rgb(188 255 247 / 59%);
        h3{
            font-family: cursive;
            margin-bottom: 0px;
            text-align: center;
            padding-top: 30px;
        }
        .social-media-logos{
            padding: 20px 550px;
            display: flex;
            justify-content: space-around;
            img{
                width: 80px;
            }
        }
        h2{
            margin-bottom: 0px;
        }
    }
</style>