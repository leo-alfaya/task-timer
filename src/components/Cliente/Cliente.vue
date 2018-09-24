<template>
  <div class="cliente">
    <Sidebar/>
    <ClienteContent/>
  </div>
</template>

<script>
import Sidebar from '../common/Sidebar.vue';
import ClienteContent from './ClienteContent.vue';

export default {
  name: 'Cliente',
  components: {
    Sidebar,
    ClienteContent,
  },
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
