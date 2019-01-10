<template>
	<div id="card">
		<Title></Title>
		<Bild></Bild>
		<Info></Info>
	</div>
</template>

<script>
	import Bild from '@/components/Bild.vue';
	import Info from '@/components/Info.vue';
	import Title from '@/components/Title.vue';
	export default {
		name: 'Card',
		components: {
			Bild
		}
	}
</script>

<style>
	#card {
		background-color: blue;
	}
</style>