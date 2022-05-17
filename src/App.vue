<template>
	<div>
		<sidebar-bank/>
		<router-view></router-view>
	</div>
</template>

<script>
import SidebarBank from './components/sidebank.vue'

import './assets/tailwind.css'

	export default {
		components: {
			SidebarBank
		},
		data() {
			return {
				title: 'leopard 1'
			}
		},
		methods: {

		}
	}
</script>

<style lang="scss" scoped>

</style>