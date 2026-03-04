<script setup>

</script>

<template>
  <div :class="['container']">
    <h1>Mood Switcher</h1>

    <p>{{ moodMessage }}</p>

    <button>Happy</button>
    <button>Sad</button>
    <button>Angry</button>
  </div>
</template>

<style scoped>
.container {
  padding: 40px;
  text-align: center;
  transition: 0.3s;
  color: black;
  border-radius: 20px;
}

.happy {
  background-color: #ffe066;
}

.sad {
  background-color: #74c0fc;
}

.angry {
  background-color: #ff6b6b;
}

button {
  margin: 10px;
  padding: 10px 15px;
  cursor: pointer;
  border-radius: 10px;
}
</style>