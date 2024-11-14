
<script setup lang="ts">
    import Container from '../container/index.vue'
    import Card from '../ui/card/index.vue'
</script>

<template>
    <section id="juniors">
        <h2 class="juniors-title">PDP Junior  kurslari</h2>
        <Container>
            <div class="juniors-wrapper">
                <Card v-for="(_, i) in 4" :key="i"/>
            </div>
        </Container>
    </section>
</template>


<style lang="scss" src="./style.scss" scoped>

</style>