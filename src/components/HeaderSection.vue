<template>
  <div class="container-fluid main-bg">
    <div class="row container m-auto">
      <div class="col-6">
        <h1>Award winning <br> toys for childern</h1>
        <p>creative,timeless toys for childern of all ages!</p>
        <button type="button" class="btn bg-btn text-white">SHOP NOW</button>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderSection',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .main-bg{    
    background-image: url('../assets/section1BG.png');
    background-position:center;
    background-size:contain;
    background-repeat: no-repeat;
    padding: 100px 0;
    background-color:#f8f4ed;
  }

  p{
    color: #666;
  }
 
</style>
