<script setup>
defineProps({
  name: {
    default: "Post Malone",
    type: String,
  },
});
</script>

<template>
  <div class="greetings">
    <!-- Profile pic -->
    <img
      alt="Post Malone"
      class="profile-pic"
      src="@/assets/images/post.jpg"
      width="300"
      height="300"
    />

    <!-- Profile name tag/title -->
    <h1 class="tag green">{{ name }}</h1>

    <!-- Sub-title -->
    <h3 class="sub-title">Blending Genres, Breaking Boundaries</h3>
  </div>
</template>
