<template>
  <div class="page">
    <h1>{{name}}</h1>
   
    <div class="paintings">
      <div class="self">
        <img src="/static/images/self.jpg">
      </div>
      <div class="earth">
        <img src="/static/images/earth.jpg">
      </div>
      <div class="smoothies">
        <img src="/static/images/smoothies.jpg">
      </div>
      <div class="violin">
        <img src="/static/images/violin.jpg">
      </div>
       <div class="marble">
        <img src="/static/images/marblev.jpg">
      </div>
      <div class="bird">
        <img src="/static/images/bird.jpg">
      </div>
    </div>
    
  </div>
</template>
<style>
  @import url('https://fonts.googleapis.com/css?family=Montserrat|Cinzel+Decorative|Meddon|Julius+Sans+One|Amatic+SC|Calligraffitti|Shadows+Into+Light|Over+the+Rainbow');
</style>

<script>
 export default {
   name: 'Paintings',
   data () {
     return {
       name: 'Paintings',
       imagePath: '/static/images/me.jpg'
     }
   }
 }
</script>

<style scoped>
.paintings {
  display: grid;
  grid-gap: 2.5vw;
  padding: 2.5vw;
  grid-template-columns: 1fr 1fr;
}
.paintings img {
  width: 46.2vw;
}
 img {
    box-shadow: 0vw 1vw 3vw black;
 }
.container {
    margin: 4vw;
    padding: 2vw;
 }
 .page {
    background-color: #F5F5F5;
    box-shadow: 0vw 1vw 6vw black;
    margin-bottom: 10vw;
 }
 h1 {
    color: black;
    padding-top: 7vw;
    padding-bottom: 2vw;
    font-family: 'Julius Sans One', cursive;
    font-weight: lighter;
    font-size:calc(12px + 3vw);
    line-height: 70%;
 }
 .footer {
  text-align: left;
 }
 .footer a {
  text-decoration: none;
  font-size: 5vw;
  font-family: 'Shadows Into Light', cursive;
  color: black;
  padding: 2vw 2vw 7vw 2vw;
  text-align: center;
  float: top;
}
.footer img {
  box-shadow: none;
  height: 4.5vw;
  width: 4.5vw;
  padding-left: 5vw;
}
 template {
    border: 0;
    margin: 0;
    padding: 0;
 }
</style>


