<template>
  <HeaderItem />
  <div class="content">
    <SearchResultsItem />
    <ShoppingCartItem />
  </div>
</template>

<script>
import HeaderItem from './components/HeaderItem.vue';
import SearchResultsItem from './components/SearchResultsItem.vue';
import ShoppingCartItem from './components/ShoppingCartItem.vue'

export default {
  name: 'App',
  components: {
    HeaderItem,
    SearchResultsItem,
    ShoppingCartItem,
  }
}
</script>

<style lang="scss">
@import "./styles.scss";
#app {
  font-family: Arial, Helvetica, sans-serif;
  color: $text-color;
  background-color: $background-color;
  width: 100%;
  min-height: 100vh;
  text-align: center;
  .content {
    display: flex;
    justify-content: space-evenly;
  }
}
</style>
