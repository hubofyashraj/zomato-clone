<template>
  <div id="backg">
  </div>
  <div id="base">
    <header>
      <div>
        <NavigationBar/>
        <h1>Zomato</h1>
        <h3>Discover the best food & drinks in Jaipur</h3>
        <SearchBar/>
      </div>
    </header>
    <SuggestionBar/>
    <CollectionBar/>
    <PopularLocalities/>
    <GetApp/>
    <ExploreOptions/>
    <AboutZomato/>
    <footer>
      <p>By continuing past this page, you agree to our Terms of Service, Cookie Policy, Privacy Policy and Content Policies. All trademarks are properties of their respective owners. 2008-2022 © Zomato™ Ltd. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
import NavigationBar from "@/components/NavigationBar";
import SearchBar from "@/components/SearchBar";
import SuggestionBar from "@/components/SuggestionBar";
import CollectionBar from "@/components/CollectionBar";
import PopularLocalities from "@/components/PopularLocalities";
import GetApp from "@/components/GetApp";
import ExploreOptions from "@/components/ExploreOptions";
import AboutZomato from "@/components/AboutZomato";

export default {
  name: 'App',
  components: {
    AboutZomato,
    ExploreOptions,
    GetApp,
    PopularLocalities,
    CollectionBar,
    SuggestionBar,
    SearchBar,
    NavigationBar,
  }
}
</script>

<style>
body{
  margin: 0;
}
#backg{
  background-color: #42b983;
  height: 47.5em;
  width: 100%;
  position: absolute;
  z-index: -1;
  background-image: url("../public/img.avif");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

}
header div h1{
  font-size: 6em;
  margin-top: 1.5em;
  margin-bottom: 0;
  -webkit-text-fill-color: white;
}
header div h3{
  font-size: 3em;
  -webkit-text-fill-color: white;
  margin-top: 0.3em;
  margin-bottom: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;


}
#base {
  width: 100%;
  max-width: 100rem;
  margin: 0 auto;

}

header {
  height: 50rem;
}

footer{
  text-align:left ;
  border-top: 1px #c0c0c0 solid;
  margin-bottom: 2em;
}
footer p{
  margin-top: 2em;
}

</style>