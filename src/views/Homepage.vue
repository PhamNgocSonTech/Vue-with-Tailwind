<template>
    <Navbar/>
    <Blog/>
</template>

<script>
import Blog from '../components/Blog.vue';
import Navbar from '../components/Navbar.vue';

export default {
    name: 'Homepage',
    components: { Navbar, Blog }
}
</script>

<style>

</style>