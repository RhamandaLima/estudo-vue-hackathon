<template>
    <div class="desafio-contador">
        <h2>Meu Contador</h2>
        <p><strong>Contador: </strong>{{ contador }}</p>
        <button @click="removeUm">-</button>
        <button @click="somaUm">+</button>
    </div>
</template>

<script>
export default {
    name:'DesafioContador',
    data() {
        return {
            contador: 0
        }
    },
    methods: {
        removeUm() {
            this.contador--;
        },
        somaUm() {
            this.contador++;
        }
    }
}
</script>

<style scoped>

</style>