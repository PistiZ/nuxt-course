<template>
    <header class="header">
        <ul class="nav-items">
            <li>
                <nuxt-link to="/">Home</nuxt-link>
            </li>

            <li>
                <nuxt-link to="/users">Users</nuxt-link>
            </li>
        </ul>
    </header>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    .header {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 60px;
        background-color: lightslategray;
    }

    .nav-items {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 80%;
    }
</style>
