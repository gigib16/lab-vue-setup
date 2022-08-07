<template>
  <div>
    <h2>Este es mi componente</h2>
    <p>El número es {{ numero }}</p>
    <button @click="sumar">Sumar</button>
  </div>
</template>

<script>

export default {
    data(){
        return{
            numero:0,
        };
    },

    methods: {
        sumar () {
            this.numero++;
        },
    },
};
</script>

<style></style>