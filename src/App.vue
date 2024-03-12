<script setup>
import ListagemProdutos from '@/components/ListagemProdutos.vue';
// import MenuSuperior from '@/components/MenuSuperior.vue';
import { useMonitor } from '@/composables/monitor';
const { menu } = useMonitor();

</script>

<template>
  <!-- <MenuSuperior /> -->
  <component :is="menu" />
  <ListagemProdutos />
</template>

