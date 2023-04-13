<script setup lang="ts">
defineProps<{
  msg: string;
}>();
</script>

<template>
  <div class="greetings">
    <h1 class="primary-color">{{ msg }}</h1>
    <h3>
      Download our app on the
      <a href="https://vitejs.dev/" target="_blank" rel="noopener"
        >iOS App Store.</a
      >
      <!-- or
      <a href="https://vuejs.org/" target="_blank" rel="noopener">Google Play Store</a>. -->
      <br />
      If you have any questions, contact Diarmuid at
      <a href="mailto:diarmuiddevs@proton.me">diarmuiddevs@proton.me</a>. We are
      happy to hear any &amp; all feedback or comments.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
