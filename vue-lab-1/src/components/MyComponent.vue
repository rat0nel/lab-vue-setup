<template>
  <div>
    <h2>My Component</h2>
    <p>El numero es {{ numero }}</p>
    <button @click="sumar"> Sumar </button>
  </div>
</template>

<script>
export default {
    data() {
        return {
            numero: 0
        };
    },
    methods: {
        sumar() {
            this.numero ++;
        }
    }
};
</script>

<style>

</style>