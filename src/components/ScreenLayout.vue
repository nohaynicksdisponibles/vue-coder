<template>
    <div :style="maxHeight && {height: '100vh'}">
        <NavBar class="mb-2"></NavBar>
        <div class="d-flex justify-content-center align-items-center" >
            <slot></slot>
        </div>
    </div>
</template>

<script setup>
    import NavBar from '@/components/NavBar.vue';
    import { defineProps } from 'vue';

    defineProps({
        maxHeight: Boolean
    })
</script>