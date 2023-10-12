<template>
    <div class="index">
        <h1>Index page</h1>
        <h2>{{ foo }}</h2>
        <Hello />
    </div> 
</template>

<script setup lang="ts">
    const foo = useFoo();
</script>
