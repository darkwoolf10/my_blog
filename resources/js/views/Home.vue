<template>
    <div class="posts">
        <post></post>
        <post></post>
        <post></post>
        <post></post>
        <post></post>
        <post></post>
        <post></post>
        <post></post>
    </div>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style lang="scss" scoped>
    .md-card {
        margin-top: 20px;
        width: 500px;
        display: inline-block;
        vertical-align: top;
        background-color: white;
    }

    .posts {
        display: flex;
        flex-flow: row wrap;
        justify-content: space-around;
    }
</style>