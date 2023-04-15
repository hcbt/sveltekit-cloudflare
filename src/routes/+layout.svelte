<script>
	import '$lib/styles/style.css';
	import Header from '$lib/components/Header/Header.svelte';
	import Footer from '$lib/components/Footer/Footer.svelte';
</script>

<Header />

<main>
	<slot />
</main>

<Footer />
