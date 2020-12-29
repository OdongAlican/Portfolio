/* eslint-disable */
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
        <form @submit.prevent="sendEmail">
          <div class="contact-details d-flex">
            <div class="left-contact">
              <h4>Get In Touch</h4>
              <div class="name">
                <label for="name">
                  Enter Your Name*
                </label>
                <input
                  v-model.trim="$v.name.$model"
                  :class="{
                    'is-invalid': $v.name.$error,
                    'is-valid': !$v.name.$invalid
                  }"
                  name="name"
                  type="text"
                />
                <div class="valid-feedback">Your name is valid</div>
                <div class="invalid-feedback">
                  <span v-if="!$v.name.required">Name is Required!</span>
                  <span v-if="!$v.name.minLength"
                    >Name must be atleast
                    {{ $v.name.$params.minLength.min }} letters.</span
                  >
                  <span v-if="!$v.name.maxLength"
                    >Name must be at most
                    {{ $v.name.$params.maxLength.max }} letters.</span
                  >
                </div>
              </div>
              <div class="name">
                <label for="name">
                  Enter Your email*
                </label>
                <input
                  v-model.trim="$v.email.$model"
                  :class="{
                    'is-invalid': $v.email.$error,
                    'is-valid': !$v.email.$invalid
                  }"
                  type="email"
                  name="email"
                />
                <div class="valid-feedback">Your Email is valid</div>
                <div class="invalid-feedback">
                  <span v-if="!$v.email.required">Email is Required!</span>
                  <span v-if="!$v.email.isValid"
                    >Email does not match patern!</span
                  >
                </div>
              </div>
              <div class="name">
                <label for="name">
                  Enter Your Subject*
                </label>
                <input
                  v-model.trim="$v.subject.$model"
                  :class="{
                    'is-invalid': $v.subject.$error,
                    'is-valid': !$v.subject.$invalid
                  }"
                  type="text"
                  name="subject"
                />
                <div class="valid-feedback">Your subject is valid</div>
                <div class="invalid-feedback">
                  <span v-if="!$v.subject.required">Subject is Required!</span>
                  <span v-if="!$v.subject.minLength"
                    >Subject must be atleast
                    {{ $v.subject.$params.minLength.min }} letters.</span
                  >
                  <span v-if="!$v.subject.maxLength"
                    >Subject must be at most
                    {{ $v.subject.$params.maxLength.max }} letters.</span
                  >
                </div>
              </div>
              <div class="name">
                <label for="name">
                  Enter Your Message*
                </label>
                <textarea
                  name="message"
                  v-model.trim="$v.message.$model"
                  :class="{
                    'is-invalid': $v.message.$error,
                    'is-valid': !$v.message.$invalid
                  }"
                  cols="30"
                  rows="8"
                ></textarea>
                <div class="valid-feedback">Your message is valid</div>
                <div class="invalid-feedback">
                  <span v-if="!$v.message.required">Message is Required!</span>
                  <span v-if="!$v.message.minLength"
                    >Message must be atleast
                    {{ $v.message.$params.minLength.min }} letters.</span
                  >
                  <span v-if="!$v.message.maxLength"
                    >Message must be at most
                    {{ $v.message.$params.maxLength.max }} letters.</span
                  >
                </div>
              </div>
              <button type="submit" value="Send">
                SUBMIT {{ submitstatus }}
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
        </form>
      </div>
    </div>
  </div>
</template>
<script>
import emailjs from "emailjs-com";
import {
  required,
  minLength,
  maxLength,
  email
} from "vuelidate/lib/validators";
export default {
  name: "ContactUs",
  data() {
    return {
      name: "",
      email: "",
      message: "",
      subject: ""
    };
  },
  validations: {
    name: {
      required,
      minLength: minLength(3),
      maxLength: maxLength(25)
    },
    subject: {
      required,
      minLength: minLength(5),
      maxLength: maxLength(35)
    },
    message: {
      required,
      minLength: minLength(5),
      maxLength: maxLength(500)
    },
    email: {
      required,
      email,
      isValid(value) {
        if (value === "") return true;
        // eslint-disable-next-line
        const email_regex = /^(("[\w-\s]+")|([\w-]+(?:\.[\w-]+)*)|("[\w-\s]+")([\w-]+(?:\.[\w-]+)*))(@((?:[\w-]+\.)*\w[\w-]{0,66})\.([a-z]{2,6}(?:\.[a-z]{2})?)$)|(@\[?((25[0-5]\.|2[0-4][0-9]\.|1[0-9]{2}\.|[0-9]{1,2}\.))((25[0-5]|2[0-4][0-9]|1[0-9]{2}|[0-9]{1,2})\.){2}(25[0-5]|2[0-4][0-9]|1[0-9]{2}|[0-9]{1,2})\]?$)/i;

        return new Promise(resolve => {
          setTimeout(() => {
            resolve(email_regex.test(value));
          }, 350 + Math.random() * 300);
        });
      }
    }
  },
  methods: {
    sendEmail(e) {
      this.$v.$touch();
      if (this.$v.$invalid) {
        this.submitstatus = "FAIL";
      } else {
        try {
          emailjs.sendForm(
            "service_6w8g3c6",
            "template_spjoqr9",
            e.target,
            "user_PxXQmOpuhrdfKIPjAOTQA",
            {
              name: this.name,
              email: this.email,
              message: this.message,
              subject: this.subject
            }
          );
        } catch (error) {
          console.log({ error });
        }
        this.name = "";
        this.email = "";
        this.message = "";
        this.subject = "";
        this.submitstatus = "SUCCESS";
      }
    }
  }
};
</script>
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
  outline: none;
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
