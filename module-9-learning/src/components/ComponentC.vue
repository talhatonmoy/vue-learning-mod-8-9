<script setup>
import { ref, provide, inject } from 'vue';
import Course from '../data/course.js'

</script>

<template>
    <hr>
<h2>Component C here: {{ Course }} </h2>

<input type="text" name="" v-model="Course.name" id="">

</template>

<style scoped>

</style>