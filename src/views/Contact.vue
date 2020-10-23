<template>
  <div class="about main-section">
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
              <input type="text" />
            </div>
            <div class="name">
              <label for="name">
                Enter Your email*
              </label>
              <input type="email" />
            </div>
            <div class="name">
              <label for="name">
                Enter Your Subject*
              </label>
              <input type="text" />
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
  border: 2px solid #2e344e;
  background-color: transparent;
  color: #a2a79d;
  width: 100%;
  background-color: #10121b;
  padding: 5px 5px;
}

.name input {
  height: 45px;
}

.left-contact {
  flex: 1;
}

.left-contact h4 {
  font-family: Nunito, sans-serif;
  color: #fff;
}

.right-contact {
  padding: 0 10px;
  flex: 1;
}
.name label {
  position: absolute;
  color: #a2a79d;
  margin-top: -13px;
  margin-left: 10px;
  font-size: 16px;
  background-color: #10121b;
  padding: 0 10px;
}

.phone-contact {
  display: flex;
}

.icon {
  padding: 20px;
  background: #191d2b;
  flex: 1;
  font-size: 30px;
  color: #a4acc4;
}

.icon-details {
  flex: 5;
  font-family: Nunito, sans-serif;
  background: #191d2b;
  padding-left: 10px;
}

.icon-details span {
  font-size: 22px;
  color: #fff;
  display: block;
  margin-top: 20px;
}

.icon-details p {
  color: #a2a79d;
  font-size: 16px;
}

.font-icon {
  border: 1px solid #a4acc4;
  padding: 20px;
}

.first-part {
  margin-bottom: 20px;
}

button {
  background-color: #0d7dfa;
  border: none;
  width: 120px;
  height: 50px;
  color: #fff;
  font-weight: bold;
  font-size: 14px;
  margin-top: 10px;
  cursor: pointer;
}

@media only screen and (max-width: 1024px) {
  .contact-details {
    flex-direction: column;
    width: 95%;
  }

  .right-contact {
    margin-top: 20px;
  }
}
</style>
