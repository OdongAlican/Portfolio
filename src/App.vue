<template>
  <div id="app">
    <div id="nav" class="col-md-2 mx-0 px-0">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/resume">Resume</router-link>
      <router-link to="/projects">Projects</router-link>
      <router-link to="/contacts">Contacts</router-link>
    </div>
    <div class="col-md-10 mx-0 px-0">
      <router-view />
    </div>
  </div>
</template>

<style>
#app {
  text-align: center;
  display: flex;
  height: 100%;
}

#nav {
  padding: 30px;
  background: #000;
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.sections {
  height: 100vh;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
