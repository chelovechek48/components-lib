<template>
  <div class="container">
    <slot />
  </div>
</template>

<style scoped>
.container {
  max-width: 40rem;
  margin: 0 auto;
  padding: 1rem;
  background-color: gainsboro;
  border: 3px solid black;
}
</style>