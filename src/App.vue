<script setup lang="ts">
import PageHeader from './components/page/PageHeader.vue'
import PageFooter from './components/page/PageFooter.vue'
import AlertMessage from './components/AlertMessage.vue'
</script>

<template>
	<PageHeader />

	<main class="container container-padding typography">
		<h1>Headline 1</h1>
		<h2>Headline 2</h2>
		<h3>Headline 3</h3>
		<h4>Headline 4</h4>
		<h5>Headline 5</h5>
		<h6>Headline 6</h6>
		<AlertMessage type="error" title="Error Title"> Error Text </AlertMessage>
	</main>

	<PageFooter />
</template>
