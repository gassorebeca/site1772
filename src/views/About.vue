<template>
  <div id="about" class="about">
    <div class="container">
      <div class="paddingItens">
        <h3 class="title">Our Mission</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis ut consequat nisl, vel tincidunt lacus. Suspendisse semper nibh id mattis aliquet. Fusce tincidunt cursus ipsum, et dignissim nunc ullamcorper quis. Vivamus sodales gravida quam vulputate tincidunt. </p>
      </div>
      <div class="gridColumn paddingItens">
        <div>
					<img src="../assets/icons/robot.png">
          <h2>Missão 1</h2>
          <p>Some representative placeholder content for the three columns of text below the carousel. This is the first column.</p>
        </div>
        <div>
					<img src="../assets/icons/atom.png">
					<h2>Missão 2</h2>
          <p>Some representative placeholder content for the three columns of text below the carousel. This is the first column.</p>
        </div>
        <div>
					<img src="../assets/icons/human.png">
					<h2>Missão 3</h2>
          <p>Some representative placeholder content for the three columns of text below the carousel. This is the first column.</p>
        </div>
      </div>
      <div class="container new-section">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/tChoEs15rwg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h2 {
	color: var(--dark-blue);
	font-family: 'Bebas Neue', cursive;
	font-size: 30px;
	margin-bottom: 15px;
}
h2:hover {
	color: var(--yellow);
}

.about {
  height: 100vh;
	background: var(--backgrond-grey);
}

.paddingItens {
  padding: 2% 10%;
}

img {
	height: 200px;
	margin-bottom: 10px;
}

</style>
