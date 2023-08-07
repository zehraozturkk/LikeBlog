<template>
    <section class="post-list">

        <PostPreview
        id="1"
        thumbnail="https://pilbox.themuse.com/image.jpg?filter=antialias&h=385&opt=1&pos=top-left&prog=1&q=keep&url=https%3A%2F%2Fcms-assets.themuse.com%2Fmedia%2Flead%2F01212022-1047259374-coding-classes_scanrail.jpg&w=700"
        title="hello there"
        previewText="this is my firsrr psot"
        />
        <PostPreview
        id="2"
        thumbnail="https://pilbox.themuse.com/image.jpg?filter=antialias&h=385&opt=1&pos=top-left&prog=1&q=keep&url=https%3A%2F%2Fcms-assets.themuse.com%2Fmedia%2Flead%2F01212022-1047259374-coding-classes_scanrail.jpg&w=700"
        title="hello there-secondtime"
        previewText="this is second firsrr psot"
        />
        <PostPreview
        id="3"
        thumbnail="https://pilbox.themuse.com/image.jpg?filter=antialias&h=385&opt=1&pos=top-left&prog=1&q=keep&url=https%3A%2F%2Fcms-assets.themuse.com%2Fmedia%2Flead%2F01212022-1047259374-coding-classes_scanrail.jpg&w=700"
        title="hi"
        previewText="this is my second psot"
        />
    </section>
</template>


<script>
import PostPreview from '@/components/Posts/PostPreview'

export default{
  components:{
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