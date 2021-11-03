<script setup>

defineProps({
	msg: String
});
</script>

<script>
export default {
	data() {
		return {
		select: ['Yes','Maybe']
		}
	}
};
</script>

<template>
	<div>
		<h1>{{ msg }}</h1>

		<input type="checkbox" id="Yes" value="Yes" v-model="select" />
		<label for="Yes">Yes</label>
		<input type="checkbox" id="No" value="No" v-model="select" />
		<label for="No">No</label>
		<input type="checkbox" id="Maybe" value="Maybe" v-model="select" />
		<label for="Maybe">Maybe</label>
		<input type="checkbox" id="Why" value="Why" v-model="select" />
		<label for="Why">Why</label>
		<input type="checkbox" id="LoveMe" value="LoveMe" v-model="select" />
		<label for="LoveMe">LoveMe</label>
		<br/>
		<br/>
		<span>Vous avez choisi: {{ select }}</span>
	</div>
</template>

<style scoped>
label {
	color: #42b983;
}
</style>
