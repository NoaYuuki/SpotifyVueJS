<template>
  <div id="app" class="central-box">
      <h1>Welcome to your favorite songs !</h1><br>
      <p>Here you will find all your favorite songs. Simply add a title to this list by marking it with a star!</p>
    <router-view/>
  </div>
</template>

<style>
body{
  background-color: #191414;
}

h1{
    font-weight: 600;
}

.central-box{
    margin: 0 200px; 
    color: grey;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #ffffff;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
