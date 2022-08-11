<template>
  <component :is="'script'">
    <script src="https://kit.fontawesome.com/cefbadd795.js" crossorigin="anonymous"></script>
  </component>
	<div class="top">
		<div class="top-inside">
      <h1>kema-dev</h1>
      <h3>Improve your efficiency, keep your privacy</h3>
    </div>
	</div>
</template>

<script>
export default {
	name: "App",
	components: {},
	data() {
		return {
		};
	},
};
</script>

<style lang="css">
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: white;
}

.top {
	position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 65vh;
}
.top::before {
	content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 65vh;
  background-image: url('./assets/img/data_flow_2_full.jpg');
  background-size: cover;
  filter: opacity(70%);
  z-index: -1;
}
.top-inside {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  top: 0;
  left: 0;
  width: 100%;
  height: 65vh;
}

h1, h2, h3, h4, h5, h6 {
  margin: 0;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}

h1 {
  font-size: 3.5rem;
  font-weight: 300;
  margin-bottom: 2rem;
}

h3 {
  font-size: 1.5rem;
  font-weight: 300;
  margin-bottom: 0.5rem;
}

div {
	margin: 0;
}

html,
body {
	background-color: #555555;
	margin: 0;
	padding: 0;
}
</style>
