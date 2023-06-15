<template>
    <div class="card" style="width: 18rem; height: 450px; margin: 5px 5px;">
        <img :src="image" class="card-img-top" style="height: 300px;" alt="...">
        <div class="card-body" style="height: 60px;">
            <div style="height: 80px;">
                <h5 class="card-title ellipsis">{{ title }}</h5>
            </div>
        
            <a href="#" class="btn btn-primary" @click="click">Go somewhere</a>
        </div>
    </div>
</template>

<script setup>
    import { defineProps } from 'vue';

    defineProps({
        title: String,
        description: String,
        image: String
    })

    function click() {
        console.log("TEST")
    }
</script>

<style>
.ellipsis {
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    overflow: hidden;
  }
</style>