<template>
    <div class="post-page">
       <PostList />
    </div>
</template>

<script>
import PostList from '@/components/Posts/PostList'
export default {
    components: {
        PostList
    }
}
</script>

<style scoped>
.posts-pagew {
    display: flex;
    justify-content: center;
    align-items: center;
}


</style>