<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam nam repudiandae natus amet tenetur soluta nemo, itaque dignissimos voluptatibus odit ipsum mollitia nobis minima rem. Voluptatibus reiciendis ipsa placeat? Quaerat.</p>
        <PostButton/>
    </div>
</template>

<script lang="ts" setup>
    import PostButton from './PostButton.vue';
</script>
<style scoped>
    .post-card{
        border-radius: 15px;
        padding: 10px;
        margin: 5px;
        border: 2px solid #000000;
    }
</style>