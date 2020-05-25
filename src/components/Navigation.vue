<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>
      </v-col>      
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'AppNavigation',
    // data: () => ({
    // }),
  }
</script>
