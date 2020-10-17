<template>
  <div class="text-center success">
    <i class="far fa-hand-spock"></i>
    <h1 class="mt-4">Congrats</h1>
    <h2>
      <slot></slot>
    </h2>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.success {
  color: #999;
  font-size: 10rem;
}
</style>