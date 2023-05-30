<script>
export default (await import('vue')).defineComponent({
    name: "AppTitle"
})

</script>

<template>
    <h1>La mia prima app con Vite!</h1>
</template>

<style scoped>
h1 {
    color: rgb(255, 197, 1);
    text-shadow: 4px 4px black;
}
</style>