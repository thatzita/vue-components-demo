<template>
	<div>
		<img v-bind:src="url" />
	</div>
</template>

<script>
export default {
	props: ['url']
}
</script>

<style scoped>
div {
	background-color: white;
	display: inline-block;
}
img {
	width: 140px;
	height: auto;
}
</style>
