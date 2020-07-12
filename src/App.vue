<template>
  <div id="app">
    <div id="nav" class="mx-0 px-0">
      <div class=" mx-auto photo-section">
      </div> 
      <div class="links-section mt-4 px-1">
        <router-link class="link" to="/">HOME</router-link>
        <router-link class="link" to="/about">ABOUT</router-link>
        <router-link class="link" to="/resume">RESUME</router-link>
        <router-link class="link" to="/projects">PROJECTS</router-link>
        <router-link class="link" to="/contacts">CONTACTS</router-link>
      </div>
    </div>
    <div class="mx-0 px-0 right-section">
      <router-view />
    </div>
  </div>
</template>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-size: 1vw;
}

#app {
  text-align: center;
  display: flex;
  height: 100%;
  justify-content: center;
}

.links-section {
  display: flex;
  flex-direction: column;
  border-top: 1px solid #2E344E;
  border-bottom: 1px solid #2E344E;
  padding: 4em 0;
}

#nav {
  padding: 30px;
  background: #191D2B;
  display: flex;
  flex-direction: column;
  height: 100vh;
  width: 19%;
  border: 1px solid #2E344E;
}

.right-section {
  width: 81%;
}

.sections {
  height: 100vh;

  background-color: #10121B;
}

#nav a {
  color: #aaa;
}

.photo-section {
  border: 7px solid #2E344E;
  background-color: #fff;
  border-radius: 50%;
  width: 14.5em;
  height: 14.5em;
}

.link {
  text-decoration: none !important;
  padding: 10px 0;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 17px;
  cursor: pointer;
}

.link :hover {
  background-color: #fff;
}

#nav a.router-link-exact-active {
  background-color: #0D7DFA;
  color: #fff;
} 
</style>
