<template>
  <div id="app">
    <Cliente />
  </div>
</template>

<script>
import Cliente from './components/Cliente/Cliente';

export default {
  name: 'app',
  components: {
    Cliente,
  },
};
</script>

<style lang="sass">
@import "./assets/sass/index.sass"
</style>
