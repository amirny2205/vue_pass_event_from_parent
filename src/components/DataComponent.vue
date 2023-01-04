<script setup>
 import  { ref } from 'vue'

 let data = ref('')
 
 function populateData () {
   data.value = [1,2,3]
 }
</script>

<template>
  DataComponent
  {{ data }}
</template>
