<template>
  <div id="app">
    <AudioPlayer />
  </div>
</template>

<script>
import AudioPlayer from './components/AudioPlayer.vue'

export default {
  name: 'app',
  components: {
    AudioPlayer
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-image: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
	background-repeat:no-repeat;
	background-attachment:fixed;
	color: rgba(255, 255, 255, 0.7);
	font-family: Raleway, sans-serif;
	padding: 3rem;
}
</style>
