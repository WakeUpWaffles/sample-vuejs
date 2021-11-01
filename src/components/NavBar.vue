<template>
  <div class="background">
    <img class="profile-picture" src="../../public/person.jpg"/>
    Logan Haiflich
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.background{
    background-color: #4acaa8;
    color: #d2f2e9;
    height: 100vh;
    width: 15%;
    float: right;
    font-size: 2.5rem;
    text-align: center;
}
.profile-picture{
  height: 25%;
  border-radius: 100%;
  margin: auto;
}
</style>
