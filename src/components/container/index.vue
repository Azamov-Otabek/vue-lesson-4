<script setup lang="ts"></script>

<template>
    <div class="container">
        <slot/>
    </div>
</template>

<style lang="scss" scoped>
    .container{
        max-width: 1280px;
        padding: 0 144px;
        margin: 0 auto;
    }
</style>