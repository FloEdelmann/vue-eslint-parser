<template>
    <p>{{ greeting }} World!</p>
</template>

<script>
interface Data {
    greeting: string
}

export default {
    data(): Data {
        return {greeting: "Hello"}
    },
}
</script>

<style scoped>
p {
    font-size: 2em;
    text-align: center;
}
</style>
