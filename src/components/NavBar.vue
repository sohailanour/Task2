<template>
  <nav class="navbar navbar-expand-lg ">
      <div class="container-sm">
        <router-link class="navbar-brand" to="#">Kidzo Toys</router-link>
        <button class="navbar-toggler bg-light" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon "></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/">Shop</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/">About</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/">MY Account</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/">Cart(0)</router-link>
            </li>
          </ul>

        </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<style >
    a.nav-link,
    a.navbar-brand {
        color: rgb(114, 113, 113);
    }

    a.navbar-brand {
        color: #333;
    }
</style>