<template>
  <div class="cliente__content">
    <div class="menu"></div>
  </div>
</template>

<script>

export default {
  name: 'ClienteContent',
};
</script>

<style lang="sass">
@import "../../assets/sass/index"

.cliente__content
  display: grid
  grid-template-rows: 100px auto 100px
  grid-template-areas: "menu" "area-clientes" "footer"
</style>
