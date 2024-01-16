<template>
     <section class="post-list">
      <PostPreview id="1" thumbnail="https://imageio.forbes.com/specials-images/imageserve/61d52d4e3a76ed81ac034ea8/0x0.jpg?format=jpg&height=900&width=1600&fit=bounds" title="Hello there!" previewText="This is my first post!" />
      <PostPreview id="2" thumbnail="https://imageio.forbes.com/specials-images/imageserve/61d52d4e3a76ed81ac034ea8/0x0.jpg?format=jpg&height=900&width=1600&fit=bounds" title="Hello there the second time!" previewText="This is my second post!" />
      <PostPreview id="3" thumbnail="https://imageio.forbes.com/specials-images/imageserve/61d52d4e3a76ed81ac034ea8/0x0.jpg?format=jpg&height=900&width=1600&fit=bounds" title="Hello hi!" previewText="This is my third post!" />
     
    </section>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'
export default {
    components: {
        PostPreview
    }
}
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>