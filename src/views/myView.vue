<template>
	<div>
		<h1>我是父组件</h1>
		<component v-bind:is="MyComponent"></component>
	</div>
</template>

<script>
	export default{
		name: 'myView',
		data(){
			return{
				MyComponent:() => import('../components/test.vue')
			}
		}
		
	}
</script>

<style>
</style>
