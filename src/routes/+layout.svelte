<script lang="ts">
	import '../app.css';
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<Header />

<div class="wrapper">
	<slot />
</div>

<Footer />

<style>
	.wrapper {
		width: 70%;
		margin: 0 auto;
	}
</style>
