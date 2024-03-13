<script setup>
 
  import Footer from 'vue-material-design-icons/Footer.vue';
</script>

<template>
    <footer>
        <div class="footer">
        <img src="@/assets/logoFakeStore.png" alt="Logo" />
        <h1>FakeStore</h1>
      </div>

      <div>
        Home
      </div>
      <div>
        Suporte
      </div>
      <div>
        Contatos
      </div>


    </footer>
</template>

<style scoped>
.footer {
  display: flex;
  align-items: center;
}
.footer img {
  width: 3rem;
  height: 3rem;
  margin-right: 0.5rem;
}


