<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
		<popup defaulttext="Hi" popuptext="I am here!" position="bottom"/>
		<popup defaulttext="Hi" popuptext="I am here!" position="right"/>
		<popup defaulttext="Hi" popuptext="I am here!" position="left"/>
		<popup defaulttext="Hi" popuptext="I am here!" position="top"/>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import popup from '@/components/popup.vue'

export default {
	name: 'home',
	components: {
		HelloWorld,
		popup
	}
}
</script>
