<script setup>

</script>

<template>
    <button
        class="flex items-center space-x-3 py-2 px-3 rounded-md text-center text-xl bg-green-900 hover:bg-green-600 border-none">
        <div class="mr-3">
            <slot name="licon">

            </slot>
        </div>
        <slot>
            Default Button Text
        </slot>

        <div class="ml-3">
            <slot name="ricon">

            </slot>
        </div>
    </button>
</template>

<style scoped></style>