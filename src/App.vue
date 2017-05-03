<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
			<carousel>
        <slide>
          Slide 1 REALLY BIG REALLY BIG Content
        </slide>
        <slide>
          Slide 2 REALLY BIG REALLY BIG Content
        </slide>
      </carousel>

  </div>
</template>

<script>
import Hello from './components/Hello'
import {Carousel, Slide} from 'vue-carousel'

export default {
  name: 'app',
  components: {
    Hello, Carousel, Slide
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

