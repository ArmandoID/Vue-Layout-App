<template>
	<div class="container">
		<Header />
		<div class="content">
			<LeftSide />
			
			<MainApp />
		</div>
		<Footer />
	</div>
</template>

<script setup>
import Header from './components/Header.vue'
import LeftSide from './components/LeftSide.vue'
import MainApp from './components/MainApp.vue'
import Footer from './components/Footer.vue'
</script>

<style scoped>
.container {
	display: flex;
	flex-direction: column;
}

.content {
	display: flex;
	flex: 1;
}
</style>