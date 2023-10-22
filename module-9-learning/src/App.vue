<script setup>
import { reactive, ref, provide, inject } from 'vue';
import ButtonComponent from './components/ButtonComponent.vue';
import SlottedButton from './components/ButtonWithNamedSlot.vue'

</script>

<template>
  <div class=" p-16">
    <SlottedButton>
      <!-- <template v-slot:licon>
        <svg xmlns="http://www.w3.org/2000/svg" height="0.875em" viewBox="0 0 384 512">
          <path fill="#ff0000"
            d="M73 39c-14.8-9.1-33.4-9.4-48.5-.9S0 62.6 0 80V432c0 17.4 9.4 33.4 24.5 41.9s33.7 8.1 48.5-.9L361 297c14.3-8.7 23-24.2 23-41s-8.7-32.2-23-41L73 39z" />
        </svg>
      </template> -->

      Play The Nasheed

      <template v-slot:ricon>
        <svg xmlns="http://www.w3.org/2000/svg" height="0.875em" viewBox="0 0 384 512">
          <path fill="#ff0000"
            d="M73 39c-14.8-9.1-33.4-9.4-48.5-.9S0 62.6 0 80V432c0 17.4 9.4 33.4 24.5 41.9s33.7 8.1 48.5-.9L361 297c14.3-8.7 23-24.2 23-41s-8.7-32.2-23-41L73 39z" />
        </svg>
      </template>
    </SlottedButton>
  </div>
</template>

<style scoped></style>
