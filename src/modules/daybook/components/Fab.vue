<template>
  <button class="btn btn-primary">
      <!-- <i :class="`fa fa-2x ${icon}`"></i>  Se puede hacer así también 
      o como abajo (se puede concatenar una sola vez en el atributo class de esa forma: -->
       <i class="fa fa-2x"
       :class="icon"></i>
  </button>
</template>

<script>
export default {
  props: {
    icon: {
      type: String,
      default: 'fa-plus'
    }
  }
}
</script>

<style lang="scss" scoped>
button {  
    border-radius: 100%;
    bottom: 20px;
    height: 80px;
    position: fixed;
    right: 80px;
}
</style>