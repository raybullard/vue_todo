<template>
    <Header class="app-header">
        <h1>TodoList</h1>
    </Header>
</template>

<script>
export default {
    name: "header"
}
</script>

<style scoped>
    .app-header {
        background: #333;
        color:#fff;
        text-align: center;
        padding:10px;
    }

    .app-header a {
        color:#fff;
        padding-right:5px;
    }
</style>