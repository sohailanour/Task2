<template>
    <div  id="footer" class="py-5">
        <div class="social-icons my-3">
            <img src="../assets/twitter.png" alt="">
            <img src="../assets/instagram.png" alt="">
        </div>
        Copyright 2022 WebDesign
    </div>
</template>

<script>
export default {
  name: 'FooterSec',
}
</script>

<style scoped>
    img{
        width: 20px;
        margin: 10px;
        filter: grayscale(200%);
    }

    #footer{
        border-top: 2px #f4f4f4 solid;
    }
</style>