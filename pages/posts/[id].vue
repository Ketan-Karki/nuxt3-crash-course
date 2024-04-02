<script setup>
definePageMeta({
  layout: "custom",
});

const route = useRoute();

//Fetch Single Post
const {
  data: post,
  error,
  pending,
} = useLazyFetch(`https://dummyjson.com/posts/${route.params.id}`);

useHead({
  title: "Post Detail",
});
</script>

<template>
  <div>
    <div v-if="error" class="text-2xl text-white">
      An error occurred... {{ error.message }}
    </div>
    <div v-else-if="post">
      <PostDetail :id="post.id" :title="post.title" :body="post.body" />
    </div>
    <LoadSpinner v-else />
  </div>
</template>

<style lang="css" scoped></style>
