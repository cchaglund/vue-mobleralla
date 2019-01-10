<template>
  <div class="kontor">
    <div class="cards">
		<Card></Card>
		<Card></Card>
		<Card></Card>	
	</div>
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


export default {
  name: 'kontor',
  components: {
    Footer, Card
  }
}
</script>