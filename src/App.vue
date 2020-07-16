<template>
  <div id="app">
    <div id="nav" class="mx-0 px-0">
      <div class="top-image">
        <div class=" mx-auto photo-section bg-danger opposite">
        </div>
      </div>
      <div class="links-section mt-4 px-1">
        <router-link class="link" to="/">
        <i class="fas fa-home small-screen fa-2x"></i>
        <span class="opposite">HOME</span>
        </router-link>
        <router-link class="link" to="/about">
        <i class="fas fa-address-card small-screen fa-2x"></i>
        <span class="opposite">ABOUT</span>
        </router-link>
        <router-link class="link" to="/resume">
        <i class="fas fa-info-circle small-screen fa-2x"></i>
        <span class="opposite">RESUME</span>
        </router-link>
        <router-link class="link" to="/projects">
        <i class="far fa-building small-screen fa-2x"></i>
       <span class="opposite">PROJECTS</span>
        </router-link>
        <router-link class="link" to="/contacts">
        <i class="fas fa-phone small-screen fa-2x"></i>
        <span class="opposite">CONTACTS</span>
        </router-link>
      </div>
      <div  class="copyright">
        <span>&copy; 2020 SoftEarthTech </span>
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
.main-section {
  position: absolute;
  width: 100%;
  overflow-y: auto;
  right: 0;
  top: 0;
  height: 100%;
}
.sections {
  position: absolute;
  width: 100%;
  background-color: #10121B;
  overflow-y: auto;
  height: 100%;
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
  position: fixed;
  left: 0;
}

.copyright {
  margin-top: 2em;
  font-size: 14px;
  color: #fff;
}

.right-section {
  width: 81%;
}

#nav a {
  color: #aaa;
}

.photo-section {
  border: 7px solid #2E344E;
  background-color: #fff;
  border-radius: 50%;
  width: 150px;
  height: 150px;
  background-image: url("../public/image.png"); 
  background-size: cover;
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

.main-content {
  position: absolute;
  width: 77em;
  margin: 3em 1.5em;
}

.about{
  position: absolute;
  width: 81%;
  right: 0;
}

.home {
  top: 0;
  padding: 0;
  bottom: 0;
}

.about h1 {
  font-family: Nunito,sans-serif;
  position: absolute;
  font-size: 70px;
  margin-top: 140px;
  color: #151621;
}

.home h1 {
  font-size: 45px;
  margin-top: 0;
  color: #EDF2F7;
}

.inner-section {
  width: 7em;
  height: 5px;
  background-color: #18315E;
  border-radius: 10px;
  margin-top: 5.5em;
}

.middle-section {
  width: 40%;
  border-radius: 10px;
  height: 5px;
  background-color: #0D7DFA;
}

.small-screen {
  display: none;
}

@media only screen and (max-width: 1024px) {
  .opposite {
    display: none;
  }
      .sections {
      width: 100%;
    }

    .small-screen {
      display: block;
    }

    .home h1 {
      font-size: 45px;
      margin-top: -20px;
      color: #EDF2F7;
    }
}

</style>
