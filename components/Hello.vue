<template>
    <h1>Hello component , {{  msg }}</h1>
</template>

<script setup lang="ts">
    import { ref } from 'vue'

    const msg = ref("demo")
</script>