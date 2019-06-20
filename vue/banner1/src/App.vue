<template>
  <div id="app">
    <div class ="banner">
		<div id = "iphone">
			<img class="objimg obj1" src="./assets/img/AB2_Chuck.png"></div>
			<p>{{msg}}</p>
		</div>
	</div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
	startpintnum: 5,
      msg: 'ffs'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
}
.objimg{
	border: #2c3e50 1px solid;
}
 .obj1{
	position: relative;
	top:20px;
	left:40px;
}
h1, h2 {
  font-weight: normal;
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
#iphone {
	width:750px;
	height: 360px;
	background-image:url('./assets/img/iphone.png');
	background-position: center;
	background-repeat: no-repeat;
	display: flex;
  	align-items: flex-start;
}

</style>
