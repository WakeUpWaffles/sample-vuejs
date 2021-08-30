<template>
  <div>
		<img src="../assets/profile.jpg" alt="Me!" class="profile">
    <div class="top-left"></div>
    <div class="top">
			<button class="btn-large-blue">Home</button>
			<button class="btn-large-blue">About</button>
			<button class="btn-large-blue">Experience</button>
			<button class="btn-large-blue">Projects</button>
			<button class="btn-large-blue">Contact</button>
		</div>
  </div>
</template>

<script>
export default {
  name: 'Top'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.profile{
	position: absolute;
	width: 100px;
	height: 100px;
	margin: 20px;
	border-radius: 50%;
	z-index: 10;
}

.top{
    /* Rectangle 1 */
		position: relative;
    width: 100%;
    height: 100px;
    left: 0px;
    top: 0px;
		padding-left: 220px;
		padding-top: 20px;
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
