<template>
  <div class="container">
    <h1>This is a blog page</h1>
    <ul>
      <li v-for="post in posts" :key="post.title">
        {{ post.title }}
        <p>{{ post.text }}</p>
      </li>
    </ul>
  </div>
</template>

<script>
import posts from '../assets/posts.json'

export default {
    name: 'About',

    data: function () {
    return {
        posts,
        test: 'hi'
    }
}
  }
</script>