<template>
	<div>
		<h1>{{ test }}</h1>
		<p>text</p>
	</div>
</template>

<script>
export default {
	name: "Card",
	props: {
		heading: {
			type: String,
			default: "Hello. Card",
			required: true
		}
	}
};
</script>

<style>
</style>