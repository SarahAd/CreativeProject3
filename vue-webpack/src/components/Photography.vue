<template>
  <div class="page">
    <h1>{{name}}</h1>
   
      <div class="photographs">
        <div class="itsaboy">
          <img src="/static/images/itsaboy.jpg">
        </div>
        <div class="portia">
          <img src="/static/images/portia.jpg">
        </div>
        <div class="vonniev">
          <img src="/static/images/vonniev.jpg">
        </div>
        <div class="christmas1">
          <img src="/static/images/christmas1.jpg">
        </div>
        <div class="christmas2">
          <img src="/static/images/christmas2.jpg">
        </div>
         <div class="christmas3">
          <img src="/static/images/christmas3.jpg">
        </div>
        <div class="vonnie1">
          <img src="/static/images/vonnie1.jpg">
        </div>
        <div class="vonnie2">
          <img src="/static/images/vonnie2.jpg">
        </div>
        <div class="vonnie3">
          <img src="/static/images/vonnie3.jpg">
        </div>
        <div class="cathedral">
          <img src="/static/images/cathedral.jpg">
        </div>
        <div class="green">
          <img src="/static/images/green.jpg">
        </div>
        <div class="ellisisland">
          <img src="/static/images/ellisisland.jpg">
        </div>
      </div>
    
  </div>
</template>
<style>
  @import url('https://fonts.googleapis.com/css?family=Montserrat|Cinzel+Decorative|Meddon|Julius+Sans+One|Amatic+SC|Calligraffitti|Shadows+Into+Light|Over+the+Rainbow');
</style>

<script>
 export default {
   name: 'Photography',
   data () {
     return {
       name: 'Photography',
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
  .paintings {
    display: grid;
    grid-gap: 2.5vw;
    padding: 2.5vw;
    grid-template-columns: 1fr 1fr;
  }

  .photographs {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-areas:  
                "itsaboy      portia"
                "christmas1   christmas2"
                "christmas3   christmas3"
                "vonnie1      vonnie1"
                "vonnie2      vonnie3"
                "ellisisland  green"
                "cathedral    vonniev";
    grid-gap: 2.5vw;
    padding: 2.5vw;
  }
    .photographs img {
    width: 46vw;
    }
    .itsaboy {
      grid-area: itsaboy;
    }
    .portia {
      grid-area: portia;
    }
    .vonniev {
      grid-area: vonniev;
    }
    .christmas1 {
      grid-area: christmas1;
    }
    .christmas2 {
      grid-area: christmas2;
    }
    .christmas3 {
      grid-area: christmas3;
    }
    .cathedral {
      grid-area: cathedral;
    }
    .green {
      grid-area: green;
    }
    .ellisisland {
      grid-area: ellisisland;
    }
    .vonnie1 {
      grid-area: vonnie1;
    }
    .vonnie2 {
      grid-area: vonnie2;
    }
    .vonnie3 {
      grid-area: vonnie3;
    }
    .vonnie1 img {
    width: 94.6vw;
    }
    .christmas3 img {
    width: 94.6vw;
    }
    .cathedral img {
    height: 69vw;
    }
  
</style>