<template>
  <div class="about">
    <h1 class="ml-4">
      CONTACT
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
            CONTACT
          </h1>
        </div>
        <div class="inner-section">
          <div class="middle-section"></div>
        </div>
        <div class="contact-details d-flex">
          <div class="left-contact">
            <h4>Get In Touch</h4>
            <div class="name">
              <label for="name">
                Enter Your Name*
              </label>
              <input type="text">
            </div>
            <div class="name">
              <label for="name">
                Enter Your email*
              </label>
              <input type="email">
            </div>
            <div class="name">
              <label for="name">
                Enter Your Subject*
              </label>
              <input type="text">
            </div>
            <div class="name">
              <label for="name">
                Enter Your Message*
              </label>
              <textarea name="" id="" cols="30" rows="8"></textarea>
            </div>
            <button>
              SEND MAIL
            </button>
          </div>
          <div class="right-contact">
            <div class="phone-contact first-part">
              <div class="icon">
                <div class="font-icon">
                  <i class="fas fa-phone"></i>
                </div>
              </div>
              <div class="icon-details">
                <span>Phone</span>
                <p>+256777338787</p>
              </div>
            </div>
            <div class="phone-contact first-part">
              <div class="icon">
                <div class="font-icon">
                  <i class="fas fa-envelope"></i>
                </div>
              </div>
              <div class="icon-details">
                <span>Email</span>
                <p>sandieo.2020@gmail.com</p>
              </div>
            </div>
            <div class="phone-contact">
              <div class="icon">
                <div class="font-icon">
                  <i class="fas fa-map-marker-alt"></i>
                </div>
              </div>
              <div class="icon-details">
                <span>Address</span>
                <p>Plot 19, Obiya Road Gulu-Uganda</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>

.sections {
  height: 125vh;
}

.contact-details {
  display: flex;
  width: 100%;
  margin-top: 10px;
  text-align: left;
  margin-top: 40px;
}

.name {
  margin-top: 20px;
}
.name input,
.name textarea {
  display: flex;
  flex-direction: column;
  border: 2px solid #2E344E;
  background-color: transparent;
  color: #A2A79D;
  width: 100%;
  padding: 5px 5px;
}

.name input {
  height: 45px;
}

.left-contact {
  flex: 1;
}

.left-contact h4 {
  font-family: Nunito,sans-serif;
  color: #fff;
}

.right-contact {
  padding: 0 10px;
  flex: 1;
}
.name label {
  position: absolute;
  color: #A2A79D;
  margin-top: -13px;
  margin-left: 10px;
  font-size: 16px;
  background-color:#10121B;
  padding: 0 10px;
}

.phone-contact {
  display: flex;
}

.icon {
  padding: 20px;
  background: #191D2B;
  flex: 1;
  font-size: 30px;
  color: #A4ACC4;
}

.icon-details {
  flex: 5;
  font-family: Nunito,sans-serif;
  background: #191D2B;
  padding-left: 10px;

}

.icon-details span {
  font-size: 22px;
  color: #fff;
  display: block;
  margin-top: 20px;
}

.icon-details p {
  color: #A2A79D;
  font-size: 16px;
}

.font-icon {
  border: 1px solid #A4ACC4;
  padding: 20px;
}

.first-part {
  margin-bottom: 20px;
}

button {
  background-color: #0D7DFA;
  border: none;
  width: 120px;
  height: 50px;
  color: #fff;
  font-weight: bold;
  font-size: 14px;
  margin-top: 10px;
  cursor: pointer;
}

</style>