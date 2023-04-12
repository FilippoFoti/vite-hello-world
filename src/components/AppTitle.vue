<script>

export default {
    name: "AppTitle",
    data() {
        return {
            title: "Vite",
        }
    },
    methods: {

    }
}
</script>

<template>
    <h1>La mia prima app con <span>&nbsp;{{ title }}</span>!</h1>
</template>

<style>
h1 {
    display: flex;
    justify-content: center;
    font-size: 4rem;
    color: rgba(0, 22, 50, 1);;
}

span {
    color: rgba(0, 223, 107, 1);
}

</style>