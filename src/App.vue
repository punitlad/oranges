<template>
  <Orange v-for="(fruit, index) in fruits" :key="index" :fruit="fruit" />
</template>

<script>
import Orange from './components/Orange.vue'
import data from "./data.json"

export default {
  components: {
    Orange
  }, 
  data() {
    return {
      fruits: data.citrus_fruits,
    }
  },
}
</script>

<style>

</style>
