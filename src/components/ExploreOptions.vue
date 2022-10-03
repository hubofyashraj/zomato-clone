<template>
  <p class="h">Explore options near me</p>
  <div class="container">
    <div class="cont">
      <p>Popular cuisines near me</p>
      <i class="bi-chevron-down"></i>
    </div>
    <div class="cont">
      <p>Popular restaurant types near me</p>
      <i class="bi-chevron-down"></i>
    </div>
    <div class="cont">
      <p>Top Restaurant Chains</p>
      <i class="bi-chevron-down"></i>
    </div>
    <div class="cont">
      <p>Cities We Deliver To</p>
      <i class="bi-chevron-down"></i>
    </div>

  </div>
</template>

<script>
export default {
  name: "ExploreOptions"
}
</script>

<style scoped>
.h{
  text-align: left;
  font-size: 2.5em;
  margin-top: 2.5em;
}
.container{
  display: grid;
  gap: 1.5em;
}

.cont{
  height: 5em;
  align-items: center;
  display: flex;
  border-radius: 0.5em;
  border: 1px #e6e6e6 solid;
}
.cont p{
  font-size: 2em;
  margin-left: 1em;
}

.cont i{
  margin-left: auto;
  margin-right: 1em;
}
</style>