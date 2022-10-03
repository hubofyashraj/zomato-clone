<template>
<div id="nav">
  <i class="bi-phone"></i>
  <input type="button" value="Get the App">
  <input type="button" value="Investor Relations">
  <input type="button" value="Add Restaurant">
  <input type="button" value="Log in">
  <input type="button" value="Sign up">
</div>
</template>

<script>
export default {
  name: "NavigationBar"
}
</script>

<style scoped>
  #nav{
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    -webkit-text-fill-color: aliceblue;
    align-items: center;
    height: 6em;
  }
  input{
    background: none;
    border: none;
    font-size: 20px;
    font-family: Akaash;

  }
  input[type="button"]{
    margin-left: 1em;
    margin-right: 1em;
  }
  input[value="Get the App"]{
    float: left;
    margin-right: auto;
    margin-left: 0;
    font-size: 1.25em;
  }

</style>