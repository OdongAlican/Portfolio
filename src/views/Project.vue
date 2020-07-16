<template>
  <div class="about main-section">
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
          <div class="project-grid ruby-capstone">
            <div class="project-title">
              <p>
                Ruby on Rails Project for creating Categories and Articles.
                <a href="https://guarded-refuge-63992.herokuapp.com/" target="_blank">View Project</a>
              </p>
            </div>
          </div>
          <div class="project-grid html-capstone">
            <div class="project-title">
              <p>
                Front end Project for Posting Course with HTML and CSS.
                <a href="https://raw.githack.com/OdongAlican/courses-guide/develop/" target="_blank">View Project</a>
              </p>
            </div>
          </div>
          <div class="project-grid bootstrap-captone">
            <div class="project-title">
              <p>
                Bootstrap based Project cloaning Newseek Home Page.
                <a href="https://raw.githack.com/OdongAlican/newsweek.com-home-page/develop/" target="_blank">View Project</a>
              </p>
            </div>
          </div>
        </div>
        <div class="blogs-header">
          <h1>
            ARTICLES
          </h1>
        </div>
        <div class="inner-section blogs">
          <div class="middle-section">
            <div class="blog-title"></div>
          </div>
        </div>
        <div class="blog-section">
          <div class="blog-grid first-blog medium">
            <div class="blog-title-section">
              <p>
                How can one achieve proper elements alignment on a web-page?
                Having a wonderful looking page using Grid or Flex-Boxes ...
                <a href="https://medium.com/@sandieo.2020/how-can-one-achieve-proper-elements-alignment-on-a-web-page-8e1a9618bfb2" target="_blank">
                  Read More
                </a>
              </p>
            </div>
          </div>
          <div class="blog-grid first-blog wordpress">
            <div class="blog-title-section">
              <p>
                Managing relationship among various collections in mongo database with Express/Js
                This involves attaching a created Post to its author ...
                <a href="https://blog.learningdollars.com/2020/04/26/relationship-in-mongodb-using-node-expressjs/" target="_blank">
                  Read More
                </a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>



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
  background-image: url("../../public/Courses_Desktop.png");
  background-size: cover;
  position: relative;
}

.ruby-capstone {
  background-image: url("../../public/Home_page.png");
  position: relative;
  background-size: cover;
}

.bootstrap-captone {
  background-image: url("../../public/Screen-Shot.png");
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

.medium {
  background-image: url("../../public/chess.jpeg");
  background-size: cover;
}

.wordpress {
  background-image: url("../../public/mongo.jpg");
  background-size: cover;
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

@media only screen and (max-width: 1024px) {
  .projects-section {
    display: flex;
    flex-direction: column;
    width: 98%;
    margin: auto;
  }

  .project-grid {
    margin-top: 10px;
  }

  .blog-section {
    display: flex;
    flex-direction: column;
    width: 98%;
    margin: auto;
    margin-top: 10px;
  }

  .blog-grid {
    margin-top: 10px;
  }
  
}
</style>