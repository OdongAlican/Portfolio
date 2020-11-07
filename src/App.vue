<template>
  <div id="app">
    <div id="nav" class="mx-0 px-0">
      <div class="top-image">
        <div class=" mx-auto photo-section opposite"></div>
      </div>
      <div class="links-section mt-4 px-1">
        <router-link class="link border-link exec-home" to="/">
          <i class="fas fa-home small-screen mr-2"></i>
          <span class="opposite">HOME</span>
        </router-link>
        <router-link class="link border-link" to="/about">
          <i class="fas fa-address-card small-screen mr-2"></i>
          <span class="opposite">ABOUT</span>
        </router-link>
        <router-link class="link border-link" to="/resume">
          <i class="fas fa-info-circle small-screen mr-2"></i>
          <span class="opposite">RESUME</span>
        </router-link>
        <router-link class="link border-link" to="/projects">
          <i class="far fa-building small-screen mr-2"></i>
          <span class="opposite">PROJECTS</span>
        </router-link>
        <router-link class="link border-link" to="/contacts">
          <i class="fas fa-phone small-screen mr-2"></i>
          <span class="opposite">CONTACTS</span>
        </router-link>
      </div>
      <div class="copyright">
        <span class="mt-1">&copy; 2020 SoftEarthTech </span>
        <div class="social-media-footer">
          <div class="linkedIn-footer p-1">
            <a
              href="https://www.linkedin.com/in/sunday-alican-odong-b99226b7/"
              target="_blank"
            >
              <i class="fab fa-linkedin-in fa-sm"></i>
            </a>
          </div>
          <div class="twitter-footer p-1 ">
            <a href="https://twitter.com/odongsandie" target="_blank">
              <i class="fab fa-twitter fa-sm"></i>
            </a>
          </div>
          <div class="github-footer p-1">
            <a href="https://github.com/OdongAlican" target="_blank">
              <i class="fab fa-github fa-sm"></i>
            </a>
          </div>
        </div>
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
  background-color: #10121b;
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
  border-top: 1px solid #2e344e;
  border-bottom: 1px solid #2e344e;
  padding: 4em 0;
}

.border-link {
  border-bottom: 1px solid #2e344e;
  border-left: 1px solid #2e344e;
  border-right: 1px solid #2e344e;
  width: 100%;
}

.exec-home {
  border-top: 1px solid #2e344e;
}

#nav {
  padding: 30px;
  background: #191d2b;
  display: flex;
  flex-direction: column;
  height: 100vh;
  width: 19%;
  border: 1px solid #2e344e;
  position: fixed;
  left: 0;
}

.copyright {
  display: flex;
  flex-direction: column;
  justify-content: center;
  font-size: 14px;
  color: #fff;
  height: 100%;
}

.right-section {
  width: 81%;
}

#nav a {
  color: #aaa;
}

.photo-section {
  border: 7px solid #2e344e;
  background-color: #fff;
  border-radius: 50%;
  width: 150px;
  height: 150px;
  background-image: url("../public/test.jpg");
  background-size: cover;
}

.link {
  text-decoration: none !important;
  padding: 10px 0;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 17px;
  cursor: pointer;
}

#nav a.router-link-exact-active {
  background-color: #0d7dfa;
  color: #fff;
}

.main-content {
  position: absolute;
  width: 77em;
  margin: 3em 1.5em;
}

.about {
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
  font-family: Nunito, sans-serif;
  position: absolute;
  font-size: 70px;
  margin-top: 140px;
  color: #151621;
}

.home h1 {
  font-size: 45px;
  margin-top: 0;
  color: #edf2f7;
}

.inner-section {
  width: 7em;
  height: 5px;
  background-color: #18315e;
  border-radius: 10px;
  margin-top: 5.5em;
}

.middle-section {
  width: 40%;
  border-radius: 10px;
  height: 5px;
  background-color: #0d7dfa;
}

.small-screen {
  display: none;
}

.linkedIn-footer,
.twitter-footer,
.github-footer {
  border: 2px solid gray;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.social-media-footer {
  display: flex;
  justify-content: center;
  padding: 10px 0;
}

.twitter-footer {
  margin: 0 10px;
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
    color: #edf2f7;
  }
}

@media only screen and (max-width: 500px) {
  .social-media-footer {
    flex-direction: column;
    padding: 10px;
  }

  .twitter-footer,
  .linkedIn-footer,
  .github-footer {
    margin: 2px 15px;
    width: 25px;
    height: 25px;
  }
}
</style>
