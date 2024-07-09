<template>
    <div class="header">
        <h1>Poster Shop</h1>
        <FilterItem></FilterItem>
    </div>
</template>
<script setup>
import FilterItem from './FilterItem.vue'

</script>
<style scoped lang="scss">
.header {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    h1 {
        margin-top: 2rem;
    }
}
</style>