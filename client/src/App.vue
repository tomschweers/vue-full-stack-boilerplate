<template>
  <div id="app">
    <img src="./assets/profile-pic.jpg" style="width:200px">
    <h1></h1>
    <h2>Social Links</h2>
    <ul>
      <li><a href="https://www.linkedin.com/in/tomschweers/" target="_blank">LinkedIn</a></li>
      <li><a href="https://medium.com/@tomschweers" target="_blank">Medium</a></li>
      <li><a href="https://stackoverflow.com/users/7891298/schws" target="_blank">Stack Overflow</a></li>
      <li><a href="https://github.com/tomschweers" target="_blank">GitHub</a></li>
    </ul>
    <h2>Technologies</h2>
    <ul>
      <li><a href="https://nodejs.org/en/" target="_blank">Node.js</a></li>
      <li><a href="https://expressjs.com/" target="_blank">Express.js</a></li>
      <li><a href="https://vuejs.org/" target="_blank">Vue.js</a></li>
      <li><a href="https://www.mongodb.com/" target="_blank">MongoDB</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
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

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
