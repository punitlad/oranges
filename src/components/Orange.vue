<template>
  <div class="orange">
    <h1>{{ fruit.name }}</h1>
    <img :src="fruit.image" width="500" height="500">
    <p>{{ fruit.details }}</p>
  </div>
</template>


<script>
export default {
  name: 'Orange',
  props: {
    fruit: {
      type: Object,
      required: true
    },
  }
}
</script>