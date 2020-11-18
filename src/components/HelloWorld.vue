<template>
  <div class="hello">
    <div class="jumbotron hello-content"> 
      <h1 class="text-center display-4">Welcome Home</h1>
    </div>
    <br><br><br><br>
    <!--about section-->
    <div class="container text-center">
      <article itemid="article-section">
        <h5>
          A place for vets to find resources easier, wihtout going through hoops and events happening. 
          Think of it as reading a newspaper but updated weekly on the web. What inspired this was that 
          I had trouble locating info on benefits, the complicated VA site, nad when there are people 
          who get paid to help it doesn't seem like they are helping or even care. It is my focus to 
          provide as much as I can for vets at no cost to them. This is nonprofit and any charity goes 
          toward veteran programs.
        </h5>
      </article>
    </div>
    <br><br><br><br><br><br><br>
    <!-- about author -->
    <img src="http://lickei.com/Nesdvva/wp-content/uploads/2012/01/namwall.jpg" width="300px" height="300px" alt="">
      <br><br><br>
    <div class="container text-center" itemscope itemprop="author">
      
      <div class="row">
        <div class="col-md-4">
        <h1>Experience</h1>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas ipsum 
        rerum totam, porro recusandae quidem voluptatibus 
        optio non neque sint maiores expedita dicta qui iusto maxime quod cum quasi quam.
        </div>
        <div class="col-md-4">
        <h1>Education</h1>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas ipsum 
        rerum totam, porro recusandae quidem voluptatibus 
        optio non neque sint maiores expedita dicta qui iusto maxime quod cum quasi quam.
        </div>
        <div class="col-md-4">
        <h1>Military Service</h1>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas ipsum 
        rerum totam, porro recusandae quidem voluptatibus 
        optio non neque sint maiores expedita dicta qui iusto maxime quod cum quasi quam.
        </div>
      </div>
    </div>
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
<style scoped lang="scss">

.hello {
  margin-left:5px;
  margin-right:5px;
}
.hello-content {
  background: url(https://www.blogs.va.gov/VAntage/wp-content/uploads/2018/03/Wall-2a.jpg) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top:7%;
  padding-bottom:10%;
}
.hello-content h1 {
  font-size:3em!important;
  font-weight:600!important;
  color: rgb(149, 155, 148)!important;
  text-shadow: 9px 11px 9px grey!important;
}
.hello-content h3 {
  color:#da9c0d;
}
@media (maxwidth:960px){
  .hello-content h1 {
    font-size:3em!important;
    font-weight:600!important;
    color: rgb(155, 148, 148)!important;
    text-shadow: 9px 11px 9px grey!important;
  }
  .hello-content h2 {
    font-size:2em!important;
    font-weight:500!important;
    color:teal;
  }
}
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
img {
  width: 70%;
  max-height: 60vh;
}
p {
  font-size:20px;
}
.color-primary {
  color:goldenrod!important;
}
.suggestion-box {
  background: url(https://tenderfeel.xsrv.jp/wtn/wp-content/uploads/2017/06/background-drawn-at-slant-.png) no-repeat center center; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  width: 100%;
  padding-top:110px;
  padding-bottom:90px;
}
</style>
