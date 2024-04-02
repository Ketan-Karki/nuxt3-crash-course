<script setup>
// Fetch All Posts
const { data, error, pending } = useLazyFetch(
  "https://dummyjson.com/posts?limit=10"
);

const { data: products } = useFetch("/api/products");
console.log(products);

useHead({
  title: "Home",
});
</script>

<template>
  <div>
    <div v-if="error" class="text-2xl text-white">
      An error occurred... {{ error.message }}
    </div>
    <div v-else-if="data">
      <div v-for="{ id, title, body } in data.posts" :key="id">
        <PostCard :id="id" :title="title" :body="body" />
      </div>
    </div>
    <LoadSpinner v-else />
  </div>
</template>

<style lang="scss" scoped></style>
