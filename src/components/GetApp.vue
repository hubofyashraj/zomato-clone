<template>
  <div class="base">
    <div class="pic">

      <img src="../../public/phone.avif"/></div>
    <div class="dets">
      <h1>Get the Zomato App</h1>
      <p>We will send you a link, open it on your phone to download the app</p>
      <div class="radio-cont">
        <div class="radios">
          <input type="radio" name="choice">
          <p>Email</p>
        </div>
        <div class="radios">
          <input type="radio" name="choice">
          <p>Phone</p>
        </div>
      </div>
      <div class="input-cont">
        <input type="email" placeholder="Email">
        <input type="button" value="Share App Link">
      </div>
      <p>Download app from</p>
      <div class="btns-cont">
        <input type="button" id="play">
        <input type="button" id="appstore">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "GetApp"
}
</script>

<style scoped>
.base{
  margin-top: 10em;
  background-color: #fdf9f5;
  display: flex;
}


.pic,.dets{
margin-top: 6em;
  margin-bottom: 6em;
}
.pic img{
  height: 24em;
  margin-left: 10em;
  margin-right: 3em;
  margin-top: 4em;
}
.dets h1{
  text-align: left;
  font-size: 3em;
  font-weight: unset;
  margin: 0 ;
}
.dets{
  width: 33em;
}
.dets>p{
  font-size: 1.2em;
  text-align: left;
  line-height: 2em;
}
.radio-cont {
  display: flex;

}
.radios {
  display: flex;
  width: 10em;
}
.radios input{
  margin: auto 1em;
  height: 1.3em;
  width: 1.3em;
}

.input-cont {
  display: flex;
  margin-top: 1em;
  height: auto;
  gap: 1em;
}

.input-cont input[type=email]{
  border-radius: .5em;
  border: 1px #e3e3e3 solid;
  padding-left: 1em;
  width: 75%
}

.input-cont input[type=button]{
  border-radius: .5em;
  border: none;
  background-color: #ed4f5f;
  padding: .7em;
  -webkit-text-fill-color: #fdf9f5;
  font-size: 1.5em;
}
.btns-cont{
  display: flex;
  gap: 1.5em;
}

.btns-cont>input{
  width: 10em;
  height: 3em;
  border: none;
  border-radius: 0.5em;
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