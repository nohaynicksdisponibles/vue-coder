<template>
    <ScreenLayout max-height>
        <div class="d-flex justify-content-center align-items-center">
            <div class="d-flex flex-column justify-content-center align-items-center" style="width: 65%;">
                <img src="https://fakestoreapi.com/img/81fPKd-2AYL._AC_SL1500_.jpg" class="card-img-top"
                    style="height: 300px; max-width: 300px;" alt="...">
                <p>Fjallraven - Foldsack No. 1 Backpack, Fits 15 Laptops", "price": 109.95, "description": "Your perfect
                    pack for everyday use and walks in the forest. Stash your laptop (up to 15 inches) in the padded sleeve,
                    your everyday</p>
            </div>
            <div class="mw-25" style="width: 20%;">
                <CartMini></CartMini>
            </div>
        </div>
    </ScreenLayout>
</template>

<script setup>
import CartMini from '../components/CartMini.vue';
import ScreenLayout from '../components/ScreenLayout.vue';
import { defineProps } from 'vue';

defineProps({
    items: Array
})
</script>