<template>
  <div>
    <div class="top-left">
		<img src="assets/profile.png" alt="Me!" class="profile">
	</div>
    <div class="top"></div>
    <div class="left"></div>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.left{
    /* Rectangle 2 */
    position: absolute;
    width: 100px;
    height: 100%;
    left: 0px;
    top: 0px;

    background: #2692D0;
}
.top{
    /* Rectangle 1 */
    position: absolute;
    width: 100%;
    height: 100px;
    left: 0px;
    top: 0px;

    background: #2692D0;
}
.top-left{
    /* Rectangle 3 */
    position: absolute;
    width: 220px;
    height: 220px;
    left: 0px;
    top: 0px;

    background: #2692D0;

    background: radial-gradient(circle at bottom right,transparent 120px, #2692D0 120.7px);
}

</style>
