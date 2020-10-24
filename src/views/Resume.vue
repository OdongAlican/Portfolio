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
            <span>Learning Dollars Talent (LDT)</span>
            <p>
              My position at LDT is "Freelance Full Stack Software Developer".
              My role is to develop scalable applications using ExpressJs and
              VueJS, following the agile methodology of software development. I
              also participate in writing blogs that can be used by other
              developers at LDT ( Learning Dollars Talent).
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
              At refactory Uganda, software developers are trained in technical
              skills ( including Javascript, VueJs, ExpressJs, HTML, and CSS)
              and soft skills ( including Leadership skills, lean and agile
              methodologies). They are also provided opportunities to develop
              applications for start-up companies in Uganda.
            </p>
          </div>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>2017(April) - 2017(September)</span>
          </div>
          <div class="right-section">
            <h5>Base Station Transceiver (BTS) Maintenance</h5>
            <span>Netis Uganda (Intern)</span>
            <p>
              NETIS is a telecommunication company based in Uganda. They are in
              charge of maintaining several telecommunications sites within the
              country. My role as an intern was to maintain the various
              equipment within the base transceiver stations.
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
              At Microverse, I am Learning full-stack Web Development in Ruby,
              Ruby on Rails, Javascript, React & Redux, MYSQL, HTML, and CSS.
              Microverse also ensures that students have professional skills
              besides technical skills. These soft skills include remote and
              pair programming among others.
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
              I was awarded a Bachelor of Telecommunications Engineering degree
              from Kyambogo University in Uganda. Telecommunications Engineering
              is an engineering discipline centered on electrical and computer
              engineering which seeks to support and enhance telecommunication
              systems. The work ranges from basic circuit design to strategic
              mass developments.
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
  color: #a1a9ac;
}

.inner-skills {
  display: flex;
  font-size: 18px;
  font-family: Nunito, sans-serif;
  align-items: center;
  background-color: #151621;
  width: 100%;
}

.inner-section-html,
.inner-section-css {
  width: 89%;
  background-color: #2e344e;
  height: 7px;
  margin-left: 10px;
}

.middle-section-html,
.middle-section-css {
  width: 95%;
  background-color: #0d7dfa;
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
  font-family: Nunito, sans-serif;
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
  font-family: Nunito, sans-serif;
  display: flex;
  font-size: 16px;
  padding: 2px 20px;
  border-left: 3px solid #2e344e;
  position: relative;
}

.experience-section .right-section {
  text-align: left;
  flex: 3;
  color: #a2a79d;
}

.experience-section h5 {
  color: #0d7dfa;
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
  color: #a2a79d;
}

.dummy-div {
  position: absolute;
  width: 15px;
  height: 15px;
  border: 3px solid #2e344e;
  border-radius: 50%;
  top: 0;
  left: 0;
  margin-top: 5px;
  margin-left: -9px;
  background-color: #10121b;
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
