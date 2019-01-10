<!-- <template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
 -->
<template>
	<div>
		<Jumbotron></Jumbotron>
		<div class="cards">
			<Card></Card>
			<Card></Card>
			<Card></Card>	
		</div>
	<Footer></Footer>	
	</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Footer from '@/components/Footer.vue';
import Card from '@/components/Card.vue';
import Jumbotron from '@/components/Jumbotron.vue';

export default {
  name: 'home',
  components: {
    Footer, Card, Jumbotron
  }
}
</script>

<style>
	.cards {
		display: flex;
		justify-content: space-around;
	}
</style>