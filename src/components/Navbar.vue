<template>
    <nav>
        <h1>Menu</h1>
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Comment</a></li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'Navbar',
    data () {
        return {

        }
    }
}
</script>

<style scoped>
    nav {
        text-align: center;
    }
    nav ul {
        padding: 0;
    }
    nav li {
        display: inline;
        list-style: none;
        margin: 5px;
    }
</style>