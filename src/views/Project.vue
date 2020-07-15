<template>
  <div class="about">
    <h1 class="ml-4">
      PROJECTS
    </h1>
    <div class="home sections home-page d-flex">
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="main-content">
        <div>
          <h1>
            PROJECTS
          </h1>
        </div>
        <div class="inner-section">
          <div class="middle-section"></div>
        </div>
        <div class="projects-section">
          <div class="project-grid html-capstone">
            <div class="project-title">
              <p>
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
          </div>
          <div class="project-grid ruby-capstone">
            <div class="project-title">
              <p>
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
          </div>
          <div class="project-grid rails-captone">
            <div class="project-title">
              <p>
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
          </div>
        </div>
        <div class="blogs-header">
          <h1>
            BLOGS
          </h1>
        </div>
        <div class="inner-section blogs">
          <div class="middle-section">
            <div class="blog-title"></div>
          </div>
        </div>
        <div class="blog-section">
          <div class="blog-grid first-blog">
            <div class="blog-title-section">
              <p>
                eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                Ut enim ad minim veniam, quis nostrud exercitation 
                ullamco laboris nisi ut aliquip ex ea commodo consequat
              </p>
            </div>
          </div>
          <div class="blog-grid first-blog">
            <div class="blog-title-section">
              <p>
                eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                Ut enim ad minim veniam, quis nostrud exercitation 
                ullamco laboris nisi ut aliquip ex ea commodo consequat
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>

.sections {
  height: 150vh;
}

.projects-section {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  margin-top: 20px;
  font-family: Nunito,sans-serif;
  font-size: 14px;
  color: #A2A79D;
}

.project-grid {
  margin-right: 10px;
  height: 250px;
}

.html-capstone {
  background-image: url("../../public/Home_page.png");
  background-size: cover;
  position: relative;
}

.ruby-capstone {
  background-image: url("../../public/Home_page.png");
  position: relative;
  background-size: cover;
}

.rails-captone {
  background-image: url("../../public/Home_page.png");
  position: relative;
  background-size: cover;
}

.project-title {
  position: absolute;
  height: 60px;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: #2E344E;
}

.blogs {
  margin-top: 130px;
}

.blogs-header {
  margin-top: 50px;
}

.blog-section {
  display: grid;
  grid-template-columns: 1fr 1fr;
  margin-top: 20px;
  font-family: Nunito,sans-serif;
  font-size: 14px;
}

.blog-grid {
  position: relative;
  height: 270px;
  color: #A2A79D;
  margin-right: 10px;
  border: 3px solid #2E344E;
}

.blog-title-section {
  position: absolute;
  height: 60px;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: #2E344E;
  left: 0;
}
</style>