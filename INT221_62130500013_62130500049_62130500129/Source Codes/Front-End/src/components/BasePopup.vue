<template>
   <div class="show font-serif fixed font-light bg-opacity-20 bg-black flex justify-center items-center  z-30 inset-0 overflow-y-auto overflow-x-auto">
     <div :class="classpop">
      <slot></slot>
    </div>
  </div>
</template>
<script>
export default {
  props: [ 'classpop' ]
}
</script>