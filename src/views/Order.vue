<template>
    <div>Hola Orden {{id}}! Tu matrícula es: {{plateNumber}}</div>
</template>

<script>
    export default {
        name: "Order",
        props: {
            id: String,
            plateNumber: String
        }
    }
</script>

<style scoped>

</style>
