 <template>
  <div id="app">
    <Navbar />
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Blogs />
  </div>
</template>

<script>

import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import Blogs from './components/blogs.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
    Blogs
  },
  data() {
    return {
      
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
