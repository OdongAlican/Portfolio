<template>
  <div class="about sections">
    <h1 class="ml-4">
      ABOUT ME
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
            ABOUT ME
          </h1>
        </div>
        <div class="inner-section">
          <div class="middle-section"></div>
        </div>
        <div class="details d-flex">
          <div class="image-section "></div>
          <div class="details-section">
            <h2>
              I am <span>Sunday Odong</span>
            </h2>
            <p>
              I’m a full-stack software developer, and I specialize in efficient, Ruby, Ruby on Rails, Javascript,
              React apps and CSS & HTML that just work across all platforms and browsers
            </p>
            <div class="partial name d-flex mb-2">
              <div class="first">
                <span>Title</span>
              </div>
              <div>
                <h5>: Mr.</h5>
              </div>
            </div>
            <div class="partial name d-flex">
              <div class="first">
                <span>Full Name</span>
              </div>
              <div>
                <h5>: Sunday Odong</h5>
              </div>
            </div>
            <div class="partial nationality my-2 d-flex">
              <div class="first">
              <span>Nationality</span>
              </div>
              <div>
              <h5>: Ugandan</h5>
              </div>
            </div>
            <div class="partial language d-flex">
              <div class="first">
              <span>Languages </span>
              </div>
              <div>
              <h5>: English, German, Luo</h5>
              </div>
            </div>
            <div class="partial address my-2 d-flex">
              <div class="first">
              <span>Address</span>
              </div>
              <div>
              <h5>: Plot 19, Obiya Road Gulu, Uganda</h5>
              </div>
            </div>
            <div class="partial frelance d-flex">
              <div class="first">
              <span>Freelance</span>
              </div>
              <div>
              <h5>: Available</h5>
              </div>
            </div>
            <div class="cv-download ml-2 mt-2">
              <span>DOWNLOAD CV</span>
            </div>
          </div>
        </div>
        <div class="services">
          <h1>
            SERVICES
          </h1>
        </div>
        <div class="inner-section new-section">
          <div class="middle-section"></div>
        </div>
        <div class="service-section mt-4">
          <div class="front-end grid-section">
            <i class="fab fa-accusoft fa-3x"></i>
            <h5>Web Design</h5>
            <div class="empty-div"></div>
            <div class="description">
              <p>
                This is mainly achieved using Bootstrap, HTML5 and CSS3.
                The development includes use of media queries, font-awesome icons
                and google fonts. The website is design for various screen sizes 
                including Desktop, Tab and Mobile screen sizes.
              </p>
            </div>
          </div>
          <div class="back-end grid-section mx-4">
            <i class="fab fa-react fa-3x"></i>
            <h5>Web Development(Front End)</h5>
            <div class="empty-div"></div>
            <div class="description">
              <p>
                I majorly develop single paged applications 
                using Javascript and its frame-work React and Redux.
              </p>
            </div>
          </div>
          <div class="articles grid-section">
            <i class="fas fa-server fa-3x"></i>
            <h5>Web Development(Backend End)</h5>
            <div class="empty-div"></div>
            <div class="description">
              <p>
                In the Server-side (also know as Back-end), I specialize 
                in Ruby and its frame-work of Ruby on Rails. This is many developed 
                using relational database like Postgress, SQLite or MYSQL
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.main-content {
  position: absolute;
  width: 77em;
  margin: 4em 1.5em;
}

.about{
  overflow: auto;
  position: absolute;
  width: 81%;
  right: 0;
}

.home {
  top: 0;
  padding: 0;
}

.about h1 {
  font-family: Nunito,sans-serif;
  position: absolute;
  font-size: 70px;
  margin-top: 100px;
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

.image-section {
  margin-top: 70px;
  background-image: url("../../public/img.jpg");
  height: 32em;
  width: 30em;
  background-size: cover;
  background-repeat: no-repeat;
}

.details-section {
  font-family: Nunito,sans-serif;
  margin-top: 70px;
  width: 45em;
  padding-right: 10px;
}

.details-section p {
  font-size: 16px;
  color: #6F7588;
}

.details-section span {
  color: #0D7DFA;
}

.partial span,
.partial h5 {
  color: #A0AEC0;
  font-size: 20px;
}

.partial h5 {
  margin-top: 4px;
}

.partial .first {
  width: 35%;
  display: flex;
  justify-content: flex-start;
}

.partial {
  width: 100%;
  height: 30px;
  background-color: #151621;
  padding: 0 20px;
  justify-content: flex-start;
}

.cv-download {
  background-color: #0D7DFA;
  height: 4em;
  width: 13em;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
}

.cv-download :hover {
  border-bottom: 2px solid #EDF2F7;
}
.cv-download span {
  color: #EDF2F7;
}

.sections {
  height: 170vh;
}

.services {
  margin-top: 80px;
}

.new-section {
  margin-top: 150px;
}

.service-section {
  font-family: Nunito,sans-serif;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

.grid-section {
  background-color: #191D2B;
  border: 1px solid #2E344E;
  border-top: 4px solid #2E344E;
  cursor: pointer;
  color: #fff;
  padding-top: 5px;
}

.grid-section :hover{
  color: #fff;
  transition: ease;
}

.fa-accusoft,
.fa-react,
.fa-server {
  color: #0D7DFA;
  margin: 5px 0;
}

.empty-div {
  width: 4em;
  height: 2.5px;
  margin-left: 15px;
  background-color: #2E344E;
}

.description {
  padding: 10px;
  color: #A0AEC0;
}
</style>