<template>
    <div class="container-fluid">

        <h1 class="text-center py-2">Posts</h1>

        <PostList/>
    </div>
</template>

<script>

import PostList from '../components/PostList.vue';

export default {
    name: "App",
    components: {
        PostList
    }
}
</script>

<style scoped>
</style>