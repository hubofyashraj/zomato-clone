<template>
  <h1>Collections</h1>
  <div class="aaa">
    <p>Explore curated list of top restaurant, cafes, pubs and bars in jaipur, based on trends</p>
    <p class="i"> All collection in Jaipur<i class="bi-caret-right-fill"></i></p>
  </div>
  <div class="container">
    <div class="clickers">
      <img src="../../public/bestofjaipur.avif"/>
      <div class="clickers clickers2"></div>
      <div class="dets">
        <p class="title">Best of Jaipur</p>
        <p class="count">31 Places <i class="bi-caret-right-fill"></i></p>
      </div>
    </div>
    <div class="clickers"><img src="../../public/bestofjapur2.avif"/>
      <div class="clickers clickers2"></div>
      <div class="dets">
        <p class="title">Trending This Week</p>
        <p class="count">30 Places <i class="bi-caret-right-fill"></i></p>
      </div>
    </div>
    <div class="clickers"><img src="../../public/instaworthy.avif"/>
      <div class="clickers clickers2"></div>
      <div class="dets">
        <p class="title">Insta-Worthy</p>
        <p class="count">25 Places <i class="bi-caret-right-fill"></i></p>
      </div>
    </div>
    <div class="clickers"><img src="../../public/beer.avif"/>
      <div class="clickers clickers2"></div>
      <div class="dets">
        <p class="title">Beer in a Bar</p>
        <p class="count">30 Places <i class="bi-caret-right-fill"></i></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CollectionBar"
}
</script>

<style scoped>
h1,p{
  text-align: left;
  margin: 0;
}
h1{
  margin-top: 2em;
  font-size: 3em;
  font-weight: unset;
}
.aaa{
  display: flex;
  margin-top: 0.7em;
}
.aaa p{
  font-size: 1.7em;

}
.aaa .i{
  display: flex;
  border: none;
  background: none;
  -webkit-text-fill-color: salmon;
  font-size: 1.5em;
  margin-left: auto;
  margin-right: 0;
}

.aaa i{
  -webkit-text-fill-color: salmon;
}

.container{
  display: flex;
  gap: 1em;
  margin-top: 3em;
}

.clickers{
  height: 27em;
  width: 100%;
  min-width: calc(25% - 1em);
  border-radius: 0.5em;
  overflow: hidden;
}
.clickers2{
  background: linear-gradient(rgba(0,0,0,0), #000000);
  transform: translateY(-100%);
  width: inherit;
}
.clickers img{
  height: 100%;
  border-radius: inherit;
  transform: translateX(-10%);
}
.clickers p{
  -webkit-text-fill-color: #e6e6e6;
  margin: 0;
}
.dets{
  margin-left: 1em;
  transform: translateY(-32em);
}

.title{
  font-size: 1.8em;
}

.count{
  font-size: 1.3em;
}
</style>