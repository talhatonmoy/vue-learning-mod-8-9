<script setup>
import { reactive , ref, provide, inject} from 'vue';
import ComponentA from './components/ComponentA.vue';

const course = reactive({
  name: 'MasteringVueJS',
  price: '4500'
})

provide('course', course)
</script>

<template>
  <ComponentA/>
  <h1>{{ name }}</h1>
</template>

<style scoped>

</style>
