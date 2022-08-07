<template>
  <div>
    <h2>Página de contacto</h2>
    <p>{{ myNumber }}</p>
    <button @click="add">Sumar</button>
    <ComponentVue3 />
  </div>
</template>

<script setup>

import { ref } from 'vue';
import ComponentVue3 from '../components/ComponentVue3.vue';

    const myNumber = ref(3);

    function add() {
        myNumber.value++;
        console.log(myNumber);
    }
</script>

<style>

</style>