<template>
  <div>
    <div class="base base1">
      <h1>Zomato</h1>
      <div id="country">
        <i class="bi-flag"></i>
        <p>India</p>
        <i class="bi-chevron-down"></i>
      </div>
      <div id="language">
        <i class="bi-globe"></i>
        <p>English</p>
        <i class="bi-chevron-down"></i>
      </div>
    </div>
    <div class="base base2">
      <div>
        <p class="heading">About Zomato</p>
        <p>Who We Are</p>
        <p>Blog</p>
        <p>Work With Us</p>
        <p>Investors Relations</p>
        <p>Report Fraud</p>
        <p>Contact Us</p>
      </div>
      <div>
        <p class="heading">ZOMAVERSE</p>
        <p>Zomato</p>
        <p>Feeding India</p>
        <p>Hyperpure</p>
        <p>Zomaland</p>
      </div>
      <div>
        <p class="heading">FOR RESTAURANTS</p>
        <p>Partner With Us</p>
        <p>Apps For You</p>
        <p class="heading">FOR ENTERPRISES</p>
        <p>Zomato For Work</p>
      </div>
      <div>
        <p class="heading">LEARN MORE</p>
        <p>Privacy</p>
        <p>Security</p>
        <p>Terms</p>
        <p>Sitemap</p>
      </div>
      <div>
        <p class="heading">SOCIAL LINKS</p>
        <div class="socials">
          <i class="bi-linkedin"></i>
          <i class="bi-instagram"></i>
          <i class="bi-twitter"></i>
          <i class="bi-youtube"></i>
          <i class="bi-facebook"></i>
        </div>
        <div class="btns-cont">
          <input type="button" id="play">
          <input type="button" id="appstore">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutZomato"
}
</script>

<style scoped>
.base{
  display: flex;
  gap: 1em;
}

.base1{
  align-items: center;
}
.base1 h1{
  font-size: 3em;
}
.base1>div{
  font-size: 1.5em;
  border: 1px #b2b2b2 solid;
  border-radius: 0.5em;
  display: flex;
  align-items: center;
  height: 2.3em;
  width: 6em;
}

.base1 div i{
  margin-left: auto;
  margin-right: auto;
}

.base2{
  justify-content: space-between;
  margin-bottom: 3em;
  margin-right: 3em;
}

#country{
  margin-left: auto;
}

div>p{
  text-align: left;
}

.heading{
  font-size: 1.2em;
  font-weight: bold;
  margin-top: 2em;
}

.btns-cont{
  margin-top: 2em;
  display: grid;
  gap: 1em;
}

input{
  width: 10em;
  height: 3em;
  border: none;
  border-radius: 0.5em;
}

.socials{
  font-size: 1.5em;
  display: flex;
  justify-content: space-between;
}

input[id=play]{
  background: url("../../public/gplay.webp") no-repeat;
  background-size: contain;
}

input[id=appstore]{
  background: url("../../public/appstr.webp") no-repeat;
  background-size: contain;
}
</style>