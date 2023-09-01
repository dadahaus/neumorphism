<script>
	// import { COLOR } from './../../.svelte-kit/ambient.d.ts';
	// import '../app.postcss';
	// import './styles.css';
	// import '../scss/style.css';
	import Footer from './components/Footer.svelte';
	import List from './components/List.svelte';
	// import EighthNav from './components/Eighth_nav.svelte';
	import Nav from './components/Nav.svelte';
</script>

<div class="app">

	<!-- <Eighth_nav /> -->
	<!-- <List/> -->
	<Nav></Nav>
	<main>
		<slot />
	</main>

	
	<Footer>
		<slot />
	</Footer>
</div>

<style>
a{
	color: inherit;

}
</style>
