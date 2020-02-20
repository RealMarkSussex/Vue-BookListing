<template>
    <li>{{book.title}}:{{book.author}}</li>
</template>

<script>
export default {
    name: "BookItem",
    props: ['Book']
}
</script>

<style scoped>
    li {
        display:block;
        margin: 0 10px;
        }
</style>