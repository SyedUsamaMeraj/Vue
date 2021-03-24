<template>
  <div id="header">
    <h1>Test App</h1>
  </div>
  <!-- <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div> -->
  <div id="button">
    <button class="btn">Go</button>
  </div>
  <router-view />
</template>

<style>
body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0 !important;
}

#header {
  background: #2c3e50;
  color: #fff;
  width: 100%;
  height: 70px;
  justify-content: center;
  display: flex;
  margin-bottom: 25px;
}

.btn {
  background: blue;
  color: white;
  border: none;
  padding: 10px 15px;
  border-radius: 5px;
  font-size: 18px;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
