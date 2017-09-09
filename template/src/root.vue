<template>
  <div>
    <transition appear>
      <span>root</span>
    </transition>
  </div>
</template>

<script>
export default {
};
</script>

<style scoped>
div {
  color: blue;
}

.v-enter-active, .v-leave-active {
  transition: opacity .5s ease;
}

.v-enter, .v-leave-to {
  opacity: 0;
}
</style>
