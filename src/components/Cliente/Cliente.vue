<template>
  <div class="cliente">
    <Sidebar/>
    <div class="cliente__content">
    </div>  
  </div>
</template>

<script>
import Sidebar from "../common/Sidebar"

export default {
  name: 'Cliente',
  components: {
    Sidebar,
  }
};
</script>

<style lang="sass">
@import "../../assets/sass/index"

.cliente
  width: 100vw
  min-height: 100vh
  display: grid
  grid-template-columns: 1fr 3fr
</style>
