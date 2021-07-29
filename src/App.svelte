<script>
	import "./assets/main.css";
	import "./assets/flexboxgrid/css/flexboxgrid.css";
	import "../node_modules/@fortawesome/fontawesome-free/js/all";
	import { Router, Route } from "svelte-navigator";
	import Home from "./pages/Home/Home.svelte";
	import About from "./pages/About/About.svelte";
	import Navbar from "./components/Navbar.svelte";
</script>

<link
	rel="stylesheet"
	href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css"
/>

<Router>
	<header>
		<Navbar />
	</header>
	<main>
		<div>
			<Route path="/"><Home /></Route>
			<Route path="about"><About /></Route>
		</div>
	</main>
</Router>

<style>
</style>
