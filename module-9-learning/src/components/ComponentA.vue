<script setup>
import { inject } from 'vue';
import ComponentB from './ComponentB.vue';

const course = inject('course');
const name = inject('provideFromC')
const b = inject('b')


</script>

<template>
<h2>Component A is here: {{ b }} </h2>
<p>{{ course }}</p>
 
 <h3>Moving to Component B</h3>
 <ComponentB/>
</template>

<style scoped>

</style>