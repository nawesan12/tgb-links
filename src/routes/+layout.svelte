<script>
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
	import './styles.css';
</script>

<section class="gorosito">
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</section>
