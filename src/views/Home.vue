<template>
<<<<<<< Updated upstream
  <div class="home">
  </div>
=======
	<div class="home">
		<nav-header></nav-header>
		<router-view></router-view>
		<nav-footer></nav-footer>
	</div>
>>>>>>> Stashed changes
</template>

<script>
	// @ is an alias to /src
	import NavHeader from '@/components/NavHeader.vue';
	import NavFooter from '@/components/NavFooter.vue';
	export default {
		name: 'Home',
		components: {
			NavHeader,
			NavFooter
		},
		data() {
			return {

			}
		}
	}
</script>
