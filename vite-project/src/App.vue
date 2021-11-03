<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
import Checkbox from './components/Checkbox.vue'
</script>

<template>
	<div>
		<img alt="Vue logo" src="./assets/logo.png" />
		<!-- <HelloWorld msg="Hello Vue 3 + Vite + <3" /> -->
		<!-- <Checkbox msg="À toi de jouer" /> -->
		<center>
			<ul style="width:5%">
				<li><router-link to="/">Home</router-link></li>
				<li><router-link to="/about">About</router-link></li>
			</ul>
		</center>
		<router-view></router-view>

		
	</div>
</template>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
