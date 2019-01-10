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
			Bild, Title, Info
		}
	}
</script>

<style>
	#card {
		width: 300px;
		height: 300px;
		margin: 2rem;
		border: 1px solid black;
		flex-direction: column;
		background-color: lightblue;
	}
</style>