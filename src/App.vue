<script lang="ts">
import Main from './components/Main.vue'

export default {
  name: 'App',

  components: {
    Main,
  },

  data: () => ({
    //
  }),
}
</script>

<template>
  <div class="dark">
    <div class="min-h-screen bg-twhite dark:bg-primary text-primary dark:text-white">
      <Main />
    </div>
  </div>  
</template>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html, body, #root{
  max-height: 100vh;
  max-width: 100vw;

  width: 100%;
  height: 100%;
}

*, button, input{
  border: 0;
  background: none;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}


:root {
  --primary: #000;
  --secondary: #15181C;
  --search: #202327;
  --white: #D9D9D9;
  --gray: #7A7A7A;
  --outline: #2F3336;
  --retweet: #00C06B;
  --like: #E8265E;
  --twitter: #33A1F2;
  --twitter-dark-hover: #011017;
  --twitter-light-hover: #2C8ED6;
}
</style>
