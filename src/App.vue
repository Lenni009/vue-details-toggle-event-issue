<script setup lang="ts">
const sayHi = () => console.log("hi!");
</script>

<template>
  <details @toggle="sayHi">
    <summary>This is a summary</summary>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Error laboriosam
      consectetur fugit at est quas ratione doloremque aliquid blanditiis?
      Voluptatum, eligendi voluptas! Unde magnam exercitationem perspiciatis
      autem quibusdam commodi incidunt.
    </p>
  </details>
</template>
