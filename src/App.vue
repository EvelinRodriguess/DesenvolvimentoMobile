<script setup>
import ListagemProdutos from '@/components/ListagemProdutos.vue';
// import MenuSuperior from '@/components/MenuSuperior.vue';
import { useMonitor } from '@/composables/monitor';
const { menu } = useMonitor();
import FooterSuperior from '@/components/FooterSuperior.vue';
</script>

<template>
  <!-- <MenuSuperior /> -->
  <component :is="menu" />
  <ListagemProdutos />
  <FooterSuperior />
</template>
