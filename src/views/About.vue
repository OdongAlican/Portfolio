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
                <span>Title :</span>
              </div>
              <div>
                <h5>Mr.</h5>
              </div>
            </div>
            <div class="partial name d-flex">
              <div class="first">
                <span>Full Name :</span>
              </div>
              <div>
                <h5>Sunday Odong</h5>
              </div>
            </div>
            <div class="partial nationality my-2 d-flex">
              <div class="first">
              <span>Nationality :</span>
              </div>
              <div>
              <h5>Ugandan</h5>
              </div>
            </div>
            <div class="partial language d-flex">
              <div class="first">
              <span>Languages :</span>
              </div>
              <div>
              <h5>English, German, Luo</h5>
              </div>
            </div>
            <div class="partial address my-2 d-flex">
              <div class="first">
              <span>Address :</span>
              </div>
              <div>
              <h5>Plot 19, Obiya Road Gulu, Uganda</h5>
              </div>
            </div>
            <div class="partial frelance d-flex">
              <div class="first">
              <span>Freelance :</span>
              </div>
              <div>
              <h5>Available</h5>
              </div>
            </div>
            <div class="cv-download ml-2 mt-2">
              <span>DOWNLOAD CV</span>
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
  color: #fff;
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
  color: #fff;
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
  border-bottom: 2px solid #fff;
}
.cv-download span {
  color: #fff;
}


</style>