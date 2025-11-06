<script setup>
import { ref } from 'vue'

const product = ref('Socks')
const description = ref('Comfortable cotton socks for everyday wear')
  

setTimeout(() => {
  product.value = "New Socks"
  description.value = "Socks so nice, you'll want to buy them twice"
}, 4000)

</script>

<template>
  <h1>{{ product }}</h1>
  <p>{{ description }}</p>
</template>