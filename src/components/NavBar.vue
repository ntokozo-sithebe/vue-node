<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <img class="img-fluid w-25" src="https://files.slack.com/files-pri/T02LW4RMXJQ-F06KPACMPDZ/screenshot_2024-02-20_144929.png" alt="logo">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
            <router-link to="/" class="nav-link active">
                Home
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/about" class="nav-link active">
                About
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/products" class="nav-link active">
                Products
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/product" class="nav-link active">
                Product
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/admin" class="nav-link active">
                Admin
            </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/contact" class="nav-link active">
                Contact
            </router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
    
        components:{
            

        }
        
    }
</script>

<style scoped>

</style>