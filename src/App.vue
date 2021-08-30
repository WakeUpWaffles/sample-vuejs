<template>
<div> 
  <top></top>
  <div class="left"></div>
  
  <div class="body">
    <div class="body-header">
      Home
    </div>
    HOME
  </div>
</div>
</template>

<script>
import top from './components/Top.vue';
export default {
  components: { top },
  name: "App",
};
</script>

<style scoped>
.body-header{
  margin-left: 75px;
  min-height: 50px;
}
.body{
  display:inline-block;
  vertical-align: top;
}
.left{
    /* Rectangle 2 */
    display:inline-block;
    width: 100px;
    min-height: 100vh;
    height: 100%;
    left: 0px;
    top: 0px;
    margin-right: 10px;

    background: #2692D0;
}
</style>