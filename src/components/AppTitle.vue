<template>
    <h1>{{ title }}</h1>
</template>

<script>
export default {
    setup () {
        

        return {title: "La mia prima app con Vite!"}
    },
}
</script>

<style lang="css" scoped>
    h1{
        color: red;
        text-align: center;
        font-size: 6em;
        position: absolute;
        top: 12%;
        left: 50%;
        width: 45%;
        transform: translateX(-50%);
        font-weight: 700;
    }
</style>