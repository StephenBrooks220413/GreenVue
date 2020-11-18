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
          A place for vets to find <mark>resources</mark> easier, wihtout going through hoops and events happening. 
          Think of it as reading a newspaper but updated weekly on the web. What inspired this was that 
          I had trouble locating info on <mark>benefits</mark>, the complicated <mark>VA</mark> site, nad when there are people 
          who get paid to help it doesn't seem like they are helping or even care. It is my focus to 
          provide as much as I can for vets at no cost to them. This is <mark>nonprofit</mark> and any charity goes 
          toward veteran programs.
        </h5>
      </article>
    </div>
    <br><br><br><br><br><br><br>
    <div class="container benefitsBlock">
      <h2>Veteran Benefits Guide</h2>
      Paying For College with the <a href="https://www.va.gov/education/how-to-apply/" target="_blank">GIBILL</a> and using <a href="https://studentaid.gov/h/apply-for-aid/fafsa" target="_blank">FAFSA</a> <br>
      Buying a house with <a href="https://www.veteransunited.com/lp/?src=msn&adg=mvala&desc=apply&msclkid=9e0a38f5d621106d207f6740aeadb25b&utm_source=bing&utm_medium=cpc&utm_campaign=NS%20-%20VA%20Home%20Loan%20-%20E&utm_term=applying%20for%20va%20home%20loan&utm_content=VA%20Home%20Loan%20-%20Apply" target="_blank">VeteransUnited</a>
      and obtaining <a href="https://www.va.gov/housing-assistance/home-loans/how-to-apply/" target="_blank">COE</a>. <br>
      Health Insurance for <a href="https://www.va.gov/health-care/about-va-health-benefits/va-health-care-and-other-insurance/" target="_blank">Vets</a> and <a href="https://www.va.gov/health-care/family-caregiver-benefits/champva/" target="_blank">CHAMP VA</a> for the Family. <br>
      File for disability and compensation with the <a href="https://www.va.gov/disability/" target="_blank">VA</a> and view the <a href="https://militaryveteransofdisqus.org/2021-va-disability-rates/" target="_blank">pay chart</a>. <br>
      <br>
      <strong>Call the VA Crisis Line for support. - <a href="https://www.veteranscrisisline.net/get-help/hotline#:~:text=If%20you%E2%80%99re%20a%20Veteran%20in%20crisis%20or%20concerned,days%20a%20week.%20Call%201-800-273-8255%20and%20Press%201" target="_blank">WebSite</a> | <a href="tel:1-800-273-8255">Call Now</a></strong>
    </div>
    <br><br><br><br><br><br><br>
    <!-- about author -->
    
    
    <!--info block-->
    <div class="container text-center">
      <h2>Most Searched Topics</h2>
      <br>
      <small>DIRECT LINKS TO THE INFORMATION</small>
      <br><br><br>
      <div class="row">
        <div class="col-md-6">
          Benefit Elgibility Status for Education <br>
          Benefit Elgibility Status for Disability <br>
          Benefit Elgibility Status for Health Care 
        </div>
        <br><br>
        <div class="col-md-6">
          VA Facilities Near Me <br>
          Changes made my VA benefits <br>
          Log into your <a href="https://myaccess.dmdc.osd.mil/identitymanagement/authenticate.do?execution=e1s1" target="_blank">VA benefits account</a> 
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
mark {
  background-color:rgb(221, 221, 143);
}

.benefitsBlock {
  background: url(https://www.samhealth.org/-/media/SHS/Images/000-Corporate%20locations%20and%20logos/Logos/We-Honor-Veterans-Level-Four-Logo-CO.png?h=300&w=360&la=en&hash=735F478A370846E7DB42E604EE37A7ACA19A2664) no-repeat center center; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top:7%;
  padding-bottom:10%;
  // padding-left:10%;
}
strong {
  border-top: 1px solid black;
  width:70px;
  margin-top:10px;
  padding-bottom:5px;
}
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
