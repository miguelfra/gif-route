<template>
  <div>
   <nav class="navbar navbar-expand-lg navbar-dark bg-dark bg-gradient">
  <div class="container-fluid">
    <!-- <a  href="/">Gif Routes</a> -->
    <router-link to="/" class="navbar-brand">Gif Router</router-link>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <!-- <a " href="#">Home</a> -->
          <router-link class="nav-link active"  
                       aria-current="page"
                       to="/">Home
         </router-link>
        </li>
        <li class="nav-item">
          <!-- <a  href="#">About</a> -->
          <router-link class="nav-link" to="/about">About</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/gifs">gifs</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/stickers">Stickers</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>