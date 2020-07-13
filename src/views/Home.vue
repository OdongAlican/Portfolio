<template>
  <div class="home sections home-page d-flex">
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="main-content">
      <h1>Hi, I am
        <span>Sunday Odong</span>
      </h1>
      <p>
        I’m a full-stack software developer, and I specialize in efficient, Ruby, Ruby on Rails, Javascript,
      </p>
      <p> React apps and CSS & HTML that just work across all platforms and browsers</p>
      <div class="social-media d-flex">
        <div class="linkedIn">
          <i class="fab fa-linkedin-in fa-lg"></i>
        </div>
        <div class="twitter  mx-2">
          <i class="fab fa-twitter fa-lg"></i>
        </div>
        <div class="github">
          <i class="fab fa-github fa-lg"></i>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Home",
  components: {
  }
};
</script>
<style scoped>
.main-content {
  position: absolute;
  width: 70em;
  height: 20em;
  font-family: Nunito,sans-serif;
  font-weight: 900;
  margin: 17em 8em 0;
  color: #fff;
}

.main-content h1 {
  font-size: 3.285rem;
}

.main-content p {
  font-size: 20px;
  color: #6F7588;
}
.main-content span {
  color: #037fff;
}

.social-media {
  justify-content: center;
}

.social-media div {
  display: flex;
  border-radius: 50%; 
  border: 3px solid #6F7588;
  width: 40px;
  height: 40px;
  justify-content: center;
  align-items: center;
  padding: 5px;
  cursor: pointer;
}
</style>