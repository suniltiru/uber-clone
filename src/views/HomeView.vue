<template>
  <div id="Home" class="flex flex-col h-screen">
    <div class="m-3 mb-auto">
      <div class="grid grid-cols-2 gap-3 my-3">
        <serviceSelectLarge 
          text="Ride"
          image="ride"
          image-width="74"
        />  

        <serviceSelectLarge 
          text="Food"
          image="food"
          image-width="72"
          :promo="true"
        />  
      </div>
    </div>
  </div>
</template>

<script setup>
  import serviceSelectLarge from '../components/ServiceSelectLarge.vue'
</script>
