<template>
    <ScreenLayout max-height>
        <div class="d-flex flex-column justify-content-center align-items-center" style="width: 100vw;">
            <input type="email" class="form-control mb-2" style="width: 500px;" placeholder="Ingresa tu correo electrónico">
            <input type="password" class="form-control" style="width: 500px;" placeholder="Ingresa tu contraseña">
            <div class="d-flex justify-content-center align-items-center" style="width: 100vw;">
                <button class="btn btn-primary m-2" style="width: 100px;">Login</button>
                <button class="btn btn-outline-primary" style="width: 100px;">Registrarse</button>
            </div>
        </div>
    </ScreenLayout>
</template>

<script setup>
import ScreenLayout from '@/components/ScreenLayout.vue';
</script>