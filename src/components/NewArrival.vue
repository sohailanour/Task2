<template>
  <div class="new-sec"> 
    <h2>New Arrival</h2>

    <div class="row container p-5">
      <div class="col-3 position-relative position-relative">
          <div class="cart-img ">
            <img src="../assets/cart.png" alt="">
          </div>
          <div class="toy-img">
            <img src="../assets/toy1.jpg" alt="...">
          </div>
          <div class="text-start pt-3">
            <h5>Construction Set</h5>
            <span>10.99$</span>
          </div>
      </div>
      <div class="col-3 position-relative">
      <div class="cart-img ">
          <img src="../assets/cart_check.png" alt="">
        </div>
        <div class="toy-img">
            <img src="../assets/toy2.jpg" alt="...">
          </div>
          <div class="text-start pt-3">
            <h5>Construction Set</h5>
            <span>10.99$</span>
          </div>
      </div>
      <div class="col-3 position-relative">
        <div class="cart-img ">
          <img src="../assets/cart.png" alt="">
        </div>
        <div class="toy-img">
            <img src="../assets/toy3.jpg" alt="...">
          </div>
          <div class="text-start pt-3">
            <h5>Construction Set</h5>
            <span>10.99$</span>
          </div>
      </div>
      <div class="col-3 position-relative">
        <div class="cart-img ">
          <img src="../assets/cart.png" alt="">
        </div>
        <div class="toy-img">
            <img src="../assets/toy1.jpg" alt="...">
          </div>
          <div class="text-start pt-3">
            <h5>Construction Set</h5>
            <span>10.99$</span>
          </div>
      </div>
    </div>

    <button type="button" class="btn bg-btn text-white">SHOP NOW</button>

  </div>
</template>

<script>
export default {
  name: 'NewArrival',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .new-sec{
    padding: 100px;
  }

  .new-sec div div div{
    overflow: hidden;
    border-radius: 5px;
  }

  .toy-img img{
    margin-right: auto;
    width: 200%;
    transform: translate(-25%);
  }

  span{
    font-size: 14PX;
    color: #666;
  }

.cart-img{
  position: absolute;
  width: 30px;
  z-index: 99999;
  top:20px;
  left: 30px;
}

.cart-img img{
  width: 100%;
}
</style>