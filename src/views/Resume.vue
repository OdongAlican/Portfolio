<template>
  <div class="about main-section">
    <h1 class="ml-4">
      MY SKILLS
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
            MY SKILLS
          </h1>
        </div>
        <div class="inner-section">
          <div class="middle-section"></div>
        </div>
        <div class="skills-section">
          <div class="first-section">
            <h5>HTML5</h5>
            <div class="inner-skills">
              <div class="percentage">
                95%
              </div>
              <div class="inner-section-html">
                <div class="middle-section-html"></div>
              </div>
            </div>
          </div>
          <div class="second-section">
            <h5>CSS</h5>
            <div class="inner-skills">
              <div class="percentage">
                90%
              </div>
              <div class="inner-section-css">
                <div class="middle-section-css"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="skills-section my-2">
          <div class="first-section">
            <h5>Ruby</h5>
            <div class="inner-skills">
              <div class="percentage">
                80%
              </div>
              <div class="inner-section-html">
                <div class="middle-section-html ruby"></div>
              </div>
            </div>
          </div>
          <div class="second-section">
            <h5>Ruby on Rails</h5>
            <div class="inner-skills">
              <div class="percentage">
                85%
              </div>
              <div class="inner-section-css">
                <div class="middle-section-css rails"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="skills-section">
          <div class="first-section">
            <h5>Javascript</h5>
            <div class="inner-skills">
              <div class="percentage ">
                80%
              </div>
              <div class="inner-section-html">
                <div class="middle-section-html ruby"></div>
              </div>
            </div>
          </div>
          <div class="second-section">
            <h5>React &#38; Redux</h5>
            <div class="inner-skills">
              <div class="percentage">
                80%
              </div>
              <div class="inner-section-css">
                <div class="middle-section-css ruby"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="resume-section">
          <h1>
            RESUME
          </h1>
        </div>
        <div class="inner-section resume-section-div">
          <div class="middle-section"></div>
        </div>
        <div class="working-experience">
          <i class="fas fa-briefcase"></i>
          <h3>Working Experience</h3>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>2020 - Present</span>
          </div>
          <div class="right-section">
            <h5>Full-Stack Web Developer</h5>
            <span>Learning Dollas Talent (LDT)</span>
            <p>
              My role at LDT is a fullstack software Developer, Practising
              Node JS frame work of Express for Server side language and 
              Vue JS Javascript framework for the front-end. This role is mainly freelance
              based programming and blogs writing.
            </p>
          </div>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>2019 - 2020</span>
          </div>
          <div class="right-section">
            <h5>Full-Stack Web Developer</h5>
            <span>Refactory Uganda (Bootcamp)</span>
            <p>
              At Refactory Uganda, I was involved in a three months 
              softskills training (including lean and Agile methodologies of web development) 
              and an intense six (6) months Bootcamp
              practising web development in Javascript (Vue Js) and Express JS for 
              Ugandan based companies.
            </p>
          </div>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>2017(April) - 2017(September)</span>
          </div>
          <div class="right-section">
            <h5>Base Station Transciever (BTS) Maintenance</h5>
            <span>Netis Uganda (Intern)</span>
            <p>
              NETIS is a telecommunications Company based in Uganda in charge of 
              maintaining a number of telecommunications sites within the country.
              My role as an intern was to maintain the various equipment within
              the base stations.
            </p>
          </div>
        </div>
         <div class="working-experience">
           <i class="fas fa-book"></i>
          <h3>Educational Qualifications</h3>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>2020 - Present</span>
          </div>
          <div class="right-section">
            <h5>Full-Stack Web Development</h5>
            <span>Microverse</span>
            <p>
              At microverse, I am Learning fullstack Web Development in Ruby,
              Ruby on Rails, Javascript, React  &#38; Redux, MYSQL, HTML and CSS. The course 
              also includes testing of the written code and pair programming.
              Microverse also ensure that students have professional skills besides 
              technical skills which is also included in the course.
            </p>
          </div>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>2015 - 2018</span>
          </div>
          <div class="right-section">
            <h5>Bachelor Degree</h5>
            <span>Kyambogo University Uganda</span>
            <p>
              At Kyambogo University Uganda, I was rewarded with a Bachelor
              Degree in Telecommunications Engineering. 
              Telecommunications Engineering is an engineering discipline 
              centered on electrical and computer engineering which seeks to 
              support and enhance telecommunication systems. The work 
              ranges from basic circuit design to strategic mass developments.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>

.skills-section {
  display: flex;
}

.first-section,
.second-section {
  text-align: start;
  padding: 5px 0;
  margin-top: 5px;
  flex: 1;
  color: #A1A9AC;
}

.inner-skills {
  display: flex;
  font-size: 18px;
  font-family: Nunito,sans-serif;
  align-items: center;
  background-color: #151621;
  width: 100%;
}

.inner-section-html,
.inner-section-css {
  width: 89%;
  background-color: #2E344E;
  height: 7px;
  margin-left: 10px;
}

.middle-section-html,
.middle-section-css {
  width: 95%;
  background-color: #0D7DFA;
  height: 7px;
}

.middle-section-css {
  width: 90%;
}

.javascript {
  width: 70%;
}

.react {
  width: 50%;
}

.ruby {
  width: 80%;
}

.rails {
  width: 85%;
}

.resume-section {
  margin-top: 50px;
}

.resume-section-div {
  margin-top: 120px;
}

.working-experience {
  font-family: Nunito,sans-serif;
  display: flex;
  font-size: 30px;
  align-items: center;
  color: #fff;
  margin: 10px 0;
}

.working-experience h3 {
  margin-top: 18px;
  margin-left: 10px;
}

.experience-section {
  font-family: Nunito,sans-serif;
  display: flex;
  font-size: 16px;
  padding: 2px 20px;
  border-left: 3px solid #2E344E;
  position: relative;
}

.experience-section .right-section {
  text-align: left;
  flex: 3;
  color: #A2A79D;
}

.experience-section h5 {
  color: #0D7DFA;
  font-size: 27px;
}

.experience-section span {
  color: #fff;
}

.experience-section p {
  margin-top: 10px;
}

.experience-section .left-section {
  text-align: left;
  flex: 1;
  color: #A2A79D;
}

.dummy-div {
  position: absolute;
  width: 15px;
  height: 15px;
  border: 3px solid #2E344E;
  border-radius: 50%;
  top: 0;
  left: 0;
  margin-top: 5px;
  margin-left: -9px;
  background-color: #10121B;
}

@media only screen and (max-width: 1024px) {
  .skills-section {
    display: flex;
    flex-direction: column;
  }
  .inner-skills {
    width: 90%;
  }
}

@media only screen and (max-width: 780px) {
  .experience-section {
    flex-direction: column;
  }
}
</style>