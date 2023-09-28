<template>
  <div class="home">
    <RestaurantRow/>
  </div>
</template>

<script>
// IMPORT
// import  BDD from '../Bdd.js'
// COMPONENT
import RestaurantRow from '../components/RestaurantRow.vue';
export default {
    name: 'Home',
    components: {
        RestaurantRow
    },
}
</script>

<style>

</style>