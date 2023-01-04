<script setup>
 import DataComponent from '../components/DataComponent.vue'
</script>

<template>
  Parent1
  <button> По нажатию на эту кнопку должен срабатывать populateData в DataComponent </button>
  <data-component />
</template>
