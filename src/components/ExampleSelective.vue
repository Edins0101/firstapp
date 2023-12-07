<template>
    <h1 v-if="age>=18">Eres mayor de Edad</h1>
    <h1 v-else>Eres menor de Edad</h1>
</template>
<script lang="ts" setup>
    let age = 10

</script>
<style scoped>

</style>