<script setup>

const name = "Vue dinamico";
const stylecolor = "color:Blue";
const arraycolors = ["blue","red","black"]
const activo = false

</script>

<template>
  <h1>AndyGarSer {{ name }}</h1>
  <h2 :style="stylecolor">Biografia</h2>

  <h2> {{ activo ? 'Estoy activo':'Estoy inactivo' }}</h2>

  <h2 :style="`color: ${arraycolors[2]}`">{{ arraycolors }}</h2>
</template>

<style>
h1{ color: red;}

</style>