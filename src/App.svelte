<script>
	// import "../node_modules/@fortawesome/fontawesome-free/js/all";
	// import "./assets/flexboxgrid/css/flexboxgrid.css";
	import "./assets/bootstrap/css/bootstrap-grid.min.css";
	import "./assets/bootstrap/css/bootstrap-utilities.min.css";
	import "animate.css";
	import "./assets/main.css";
	import { Router, Route } from "svelte-navigator";
	import Home from "./pages/Home/Home.svelte";
	import About from "./pages/About/About.svelte";
	import Navbar from "./components/Navbar.svelte";
</script>

<link
	rel="stylesheet"
	href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css"
/>
<link
	rel="stylesheet"
	href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css"
/>
<link
	href="https://fonts.googleapis.com/css?family=Open Sans"
	rel="stylesheet"
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
