<template>
	<div class="order">
		<order-header></order-header>
		<router-view></router-view>
		<nav-footer></nav-footer>
	</div>
</template>

<script>
	import OrderHeader from '@/components/OrderHeader.vue';
	import NavFooter from '@/components/NavFooter.vue';
	export default {
		name: 'Home',
		components: {
			OrderHeader,
			NavFooter
		},
		data() {
			return {
	
			}
		}
	}
</script>

<style>
</style>
