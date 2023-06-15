<template>
    <div class="d-flex flex-wrap justify-content-center align-items-center" style="width: 98vw;">
        <CardComponent v-for="(item, index) in items"
            :key="index" 
            :title="item.title" 
            :description="item.description" 
            :image="item.image"
        />
    </div>
</template>

<script setup>
    import { defineProps } from 'vue';
    import CardComponent from './CardComponent.vue';

    defineProps({
        items: Array
    })
</script>

<style></style>