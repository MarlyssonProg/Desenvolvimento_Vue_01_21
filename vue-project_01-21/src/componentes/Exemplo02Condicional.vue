<script setup>
let exibir = false;
let media = 6.5;
</script>

<template>
    <h1 v-if="exibir">Olá Mundo!</h1>
    <p v-if="media >= 7">Aprovado(a)</p>
    <p v-else-if="media >= 5">Em exame</p>
    <p v-else>Reprovado(a)</p>
</template>