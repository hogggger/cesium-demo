<template>
  <div class="demo-container" id="cesiumId" :ref="cesiumRef">
    <h1>Demo about cesiumJS</h1>
  </div>
</template>
<script>
import { ref } from 'vue'
const cesiumRef = ref(null)
const initCesiumFunc = ()=>{
    
}
</script>

<style scoped>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
