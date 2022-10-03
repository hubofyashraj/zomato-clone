<template>
  <p>Popular Localities in and around <strong>Jaipur</strong></p>
  <div class="container">
    <div class="cont">
      <div>
        <p class="title">C Scheme</p>
        <p class="count">353 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
      <div>
        <p class="title">Malviya Nagar</p>
        <p class="count">1097 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
      <div>
        <p class="title">Tonk Road</p>
        <p class="count">340 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
      <div>
        <p class="title">Vaishali Nagar</p>
        <p class="count">1199 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
      <div>
        <p class="title">Ml Road</p>
        <p class="count">149 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
      <div>
        <p class="title">Mansarovar</p>
        <p class="count">1462 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
      <div>
        <p class="title">Raja Park</p>
        <p class="count">471 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
      <div>
        <p class="title">Bani Park</p>
        <p class="count">144 places</p>
      </div>
      <i class="bi-chevron-right"></i>
    </div>
    <div class="cont">
        <input type="button" value="see more" >
    </div>

  </div>
</template>

<script>
export default {
  name: "PopularLocalities"
}
</script>

<style scoped>
p{
  text-align: left;
  font-size: 3em;
}
.container{
  display: grid;
  grid-gap: 1.5em;
  grid-template-columns: 1fr 1fr 1fr;
}
.cont{
  display: flex;
  width: 100%;
  min-width: calc(33.33% - 1.5em);
  height: 6.5em;
  border: 1px #e3e3e3 solid;
  border-radius: 0.5em;
}

.cont i{
  margin: auto 1.5em auto auto;
}

.title{
  font-size: 1.8em;
  margin: 0.5em 0.6em;
}
.count{
  font-size: 1.4em;
  margin: 0 0.9em;
}
input[type=button]{
  background: none;
  border: none;
  font-size: 1.5em;
  width: 100%;
  height: 100%;
  text-align: center;
}
</style>