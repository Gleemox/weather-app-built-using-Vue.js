<template>
  <div id="app">
  <main>
  <div class="search-box">
  <input type="text" class="search-box" placeholder="Search ...."/>
  </div>
</main>
</div>

</template>

<script>
export default{
name: 'app',
data(){
return {
api_key: 'aa8eb439059f83b69f78c9d4ff7bc28e'
}
}
}

</script>
<style>
*{
margin:0;
passing:0;
box-sizing:border-box;
}

body{
font-family:'montserrat',sans-serif;
}

#app{
background-image:url('./assets/cold-bg.jpg');
background-size:cover;
background-position:bottom;
transition:0.4s;
}

main{
min-height: 100vh;
padding: 25px;
background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75));
}

</style>
