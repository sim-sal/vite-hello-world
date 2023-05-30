<script>
export default (await import('vue')).defineComponent({
    name: "AppHero"
})

</script>

<template>
    <div>
        <img src="../assets/homer.jpg" alt="">
    </div>
</template>

<style scoped>
div {
    max-width: 55%;
    margin: auto;
}

img {
    max-width: 100%;
}
</style>