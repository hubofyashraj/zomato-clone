<template>
<div id="base">
  <div class="suggestion">
    <div class="pic"><img src="../../public/orderonilne.avif"/></div>
    <div class="details">
      <h1>Order Online</h1>
      <h2>Stay home and order to your doorstep</h2>
    </div>
  </div>
  <div class="suggestion">
    <div class="pic"><img src="../../public/dining.avif"/></div>
    <div class="details">
      <h1>Dining</h1>
      <h2>View the city's favourite dining venues</h2>
    </div>
  </div>
  <div class="suggestion">
    <div class="pic"><img src="../../public/nightlife.avif"/></div>
    <div class="details">
      <h1>Nightlife and Clubs</h1>
      <h2>Explore the city's top nightlife outlets</h2>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "SuggestionBar"
}
</script>

<style scoped>
#base{
  display: flex;
  margin-top: 1em;
  gap: 1.5em;
}

.suggestion{
  height: 20em;
  width: 100%;
  min-width: calc( 33.3333% - 1.5em );
  border-radius: 1em;
  border: 1px #e6e6e6 solid;
  transition: transform .2s;
}
.suggestion:hover{
  transform: scale(1.05);
}
.pic{
  width: 100%;
  height: 65%;
  border-top-left-radius: inherit;
  border-top-right-radius: inherit;
  overflow: hidden;
}
.pic img{
  width: 100%;
  transform: translateY(-15%);
}
.details{
  width: 100%;
  height: 35%;
  border-bottom-left-radius: inherit;
  border-bottom-right-radius: inherit;
}
div h1{
  text-align: left;
  font-weight: unset;
  margin-left: 1em;
  margin-bottom: 0;
  margin-top: 0.5em;
}

div h2{
  text-align: left;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
  margin-left: 1.5em;
  font-weight: unset;
  margin-top: 0.1em;
  font-size: 1.4em;
}
</style>