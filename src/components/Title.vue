<template>
<h1>{{ title }}</h1>
</template>

<script setup>
defineProps({
    title: {
        type: String,
        default: "hola mundo"
    }
})
</script>