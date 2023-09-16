<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>請洽０９１２－３４５－６７８</h3>  
     <h3>房屋照片</h3>  
      <br>
       <a href="https://photos.google.com/share/AF1QipNhcMeC_KwHR5Y0y0dwjF8ob5s1ch-1ax-Hg67hzreUtAhG33Db0VbOSTCHDpeGNg?key=cWgzLUtwZFdIUV9ZcTdSa3lWSWVhNDI0NGVRaE5R" target="_blank" rel="noopener">點我->>>看房屋</a>.
   <br>
  <br>
 <br>
 <h2></h2>
 <h2>市中心超級<b-badge>大豪宅</b-badge></h2>
  <br>
 </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
