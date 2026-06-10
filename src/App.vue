<script setup>
import content from '../content/home.json'
</script>

<template>
  <h1>{{ content.titre }}</h1>
  <div>
    <p>
      {{ content.paragraph }}
    </p>
  </div>
  <div>
    <img :src="content.picture" alt="logo artisan" class="image" />
  </div>
</template>

<style scoped>
.image {
  margin: 0 auto;
  width: 500px;
}
h1 {
  color: blueviolet;
  text-align: center;
  margin-top: 45px;
}

p {
  text-align: center;
}

div {
  margin: 0 auto;
  border: 2px red solid;
  width: 500px;
}
</style>
