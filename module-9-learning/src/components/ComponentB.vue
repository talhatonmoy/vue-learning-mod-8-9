<script setup>
import ComponentC from './ComponentC.vue';
import { provide } from 'vue';

const name = "hello from b"
provide('b', name)
</script>

<template>
<h2>Component B Here: <strong> {{ name }} </strong></h2>
<h3>Moving to component C</h3>
<ComponentC/>
</template>

<style scoped>

</style>