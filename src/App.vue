<script setup lang="ts">
    import Layout from './layout/index.vue'
    import Header from './components/header/index.vue'
    import MainLayout from './layout/main-layout.vue'
</script>

<template>
    <Layout>
        <template lang="ts" #header>
            <Header />
        </template>

        <template lang="ts" #main>
            <MainLayout/>
        </template>

        <template lang="ts" #footer>
           
        </template>
    </Layout>
</template>

<style scoped></style>
