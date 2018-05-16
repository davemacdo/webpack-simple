<template>
	<div id="app">
		<img src="../assets/dino.gif">
		<h1>\{{ msg }}</h1>
		<input type="text" v-model="msg">
	</div>
</template>

<script>
export default {
	name: 'app',
	data () {
		return {
			msg: 'I\'m sure you\'ll put something interesting here eventually.'
		}
	}
}
</script>

<style{{#sass}} lang="scss"{{/sass}}>
	@import './scss/style.scss'
</style>
