<template>

<div class ="container">
    <h3>Add New Car</h3>
  <NewCar/>
</div>

</template>

<script>
import NewCar from "../components/NewCar.vue";
export default {
    data() {
      return[]; 
      },
      components: {NewCar}        
};
</script>

<style>
/* Add any component specific styles here */
</style>