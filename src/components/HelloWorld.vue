<script>
    export default {
      methods: {
        sup(){
          alert('click')
        }
      }
    };
</script>

<template>
  <slot></slot>
  <button @click="sup">watched</button>
  sup
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
