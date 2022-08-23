<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">My name is Bagus Wicaksana.<br>Front-end Developer</h1>
    <h3 class="">Student SMK Taruna Bhakti</h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: 30px;
}

h3 {
  font-size: 2rem;
  font-weight: 500;
  color: black;
}



.greetings h1,
.greetings h3 {
  text-align: center;
  margin-top: 90px;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
