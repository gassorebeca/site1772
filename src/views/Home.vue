<template>
  <div id="home">
    <div class="cover" />
		<div class="hello">
			<h1 class="title">{{ msg }}</h1>
			<p>Somos a primeira equipe de robótica da América do Sul composta por alunos de escola pública.</p>
		</div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cover {
  height: 100%;
  width: 100%;
  background-color: transparent;
  background-image: linear-gradient(
      130deg
      , var(--dark-blue) 0%, #050d14 100%);
  opacity: 0.5;
  transition: background 0.3s, border-radius 0.3s, opacity 0.3s;
	position: absolute;
	top: 0;
	left: 0;
	z-index: 2;
}
#home {
  height: 100vh;
  width: 100%;
	position: relative;
  background: url('../assets/image3.jpg') no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.hello{
  color: var(--white);
	position: center;
  z-index: 2;
}
</style>
