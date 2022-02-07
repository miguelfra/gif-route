<template>
  <div class="footer">
      <footer class="text-center bg-dark text-white py-3 bg-gradient">
          <h3>&copy; {{year}} - Miguel Valdez</h3>
      </footer>
  </div>
</template>

<script>
export default {
    data: () => ({
        
    }),
    computed: {
        year(){
            return new Date().getFullYear();
        } 
    }
}
</script>

<style scoped>
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>