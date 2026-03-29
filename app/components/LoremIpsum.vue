<template>
  <MainContainer>
    <p
      :class="{
        'lorem-ipsum': true,
        'lorem-ipsum_underline': props.underline,
      }"
    >
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam, at.
    </p>
  </MainContainer>
</template>

<style scoped>
p {
  margin: 0;
  padding: 0;
}

.lorem-ipsum {
  font-family: sans-serif;
  font-size: clamp(1rem, 3vw, 2rem);
  font-weight: 700;
}
.lorem-ipsum_underline {
  text-decoration: underline;
}
</style>

<script setup>
const props = defineProps({
  underline: Boolean,
})
</script>