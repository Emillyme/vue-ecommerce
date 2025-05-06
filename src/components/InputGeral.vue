<script setup>
    defineProps({
        nomeLabel: String,
        type: String
    })
</script>

<template>
    <label for="">{{ nomeLabel }}</label>
    <input class="border border-gray-300 rounded w-[350px]" type="type">
</template>