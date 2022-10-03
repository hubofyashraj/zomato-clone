<template>
<div id="outer">
  <div>

    <i class="bi-geo-alt-fill"></i>
    <input placeholder="location" id="location">
  </div>
  <div class="bi-dash"></div>
  <div>
    <i class="bi-search"></i>
    <input id="search" placeholder=" Search for restaurant, cuisine or dish ">
  </div>

</div>
</template>

<script>
export default {
  name: "SearchBar"
}
</script>

<style scoped>
#outer{
  font-size: 2em;
  display: flex;
  justify-content: left;
  align-items: center;
  margin: 2.5rem auto;
  width: 90%;
  max-width: 65rem;
  height: 2.25em;
  border-radius: 0.3em;
  background: white;
}

#outer div{
  display: flex;
}
.bi-dash{
  rotate: 90deg;
  font-size: 1.5em;
  width: 0;
  justify-content: center;

}
i{
  font-size: 0.8em;
  margin-left: 0.5em;
}
i[class=bi-geo-alt-fill]{
  -webkit-text-fill-color: salmon;
}
input{
  height: 1.5em;
  border: none;
  background: none;
  outline: none;

}

input[id="search"]{
  width: 38em;
  max-width: 100%;
}
</style>