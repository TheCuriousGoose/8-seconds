<script setup lang="ts">
import { RouterLink } from 'vue-router';
</script>

<template>
    <header class="navbar navbar-expand">
        <div class="container d-flex justify-content-center my-5">
            <nav class="d-flex gap-5">
                <div class="nav-item">
                    <RouterLink to="/about" class="nav-link fw-bold">How to play</RouterLink>
                </div>
                <div class="nav-item">
                    <RouterLink to="/about" class="nav-link fw-bold">About us</RouterLink>
                </div>
            </nav>
        </div>
    </header>
    <main class="d-flex justify-content-center align-items-center mt-5 pt-5 flex-column">
        <p class="fs-big mt-3">Unleash your creativity</p>
        <p>within</p>
        <h1 class="fs-huge">8 SECONDS</h1>
        <p class="mt-4">Join or create a drawing game and let your imagination run wild!</p>
        <div class="mt-4 d-flex flex-column gap-3">
            <RouterLink to="/game" class="btn btn-primary">CREATE NEW GAME</RouterLink>
            <div class="text-center">
                <RouterLink to="/game" class="btn btn-secondary">JOIN A GAME</RouterLink>
            </div>
        </div>
    </main>
</template>
