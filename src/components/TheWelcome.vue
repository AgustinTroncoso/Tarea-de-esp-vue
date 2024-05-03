<script setup>
import{ref} from 'vue'
const titulo='Componentecon script setup'
const contador= ref(0)
function incrementar(){
  contador.value++
}

</script>

<template>
  <div>
    <h1>{{ titulo }}</h1>
    <button @click="incrementar">Incrementar</button>
    <h2>Contador:{{ contador }}</h2>
  </div>
</template>

<style scoped>
h1{
  color:blue;
}
p{
  color: greenz;
}
</style>
