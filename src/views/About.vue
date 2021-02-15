<template>
  <div class="about">
    <br /><br /><br /><br />
    <div class="container profile text-center"></div>
    <br /><br /><br />
    <div class="container text-center" itemscope itemprop="author">
      <h1 class="display-4">About the author</h1>
      <br /><br />

      <div class="row">
        <div class="col-md-4">
          <br /><br />
          <h1>Experience</h1>
          17 years in the Military <br />
          3 years of I.T. work <br />
          4 years of web development <br />
          3 years of customer service work
        </div>
        <div class="col-md-4">
          <br /><br />
          <h1>Education</h1>
          Bachelor Degree in Psychology <br />
          Certificate in FullStack from TrueCoders <br />
          Coding Certificates with Microsoft
        </div>
        <div class="col-md-4">
          <br /><br />
          <h1>Military</h1>
          12 years in the National Guard <br />
          2 1/2 years in Air Force Reserves <br />
          2 1/2 years with Army Active Duty <br />
          2 Combat Deployments and 9 natural disasters
        </div>
      </div>
    </div>
    <VetWall />
    <br /><br />
  </div>
</template>

<script>
// @ is an alias to /src
import VetWall from "@/components/VetWall.vue";

export default {
  name: "Home",
  components: {
    VetWall
  }
};
</script>

<style scoped>
.profile {
  background: url(https://images.unsplash.com/photo-1541513982013-5dc4f56697f9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 70vh;
}
</style>
