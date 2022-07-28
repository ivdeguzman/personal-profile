<script lang="ts">
	import Home from "./pages/Home.svelte";
	import Projects from "./pages/Projects.svelte";
	import Loader from "./components/Loader.svelte";
	import { fade } from "svelte/transition";

	let completed: boolean = false;
	let loader = setInterval(() => {
		completed = true;
		clearInterval(loader);
	}, 5000);
</script>

{#if completed == false}
	<div transition:fade>
		<Loader />
	</div>
{:else}
	<main>
		<Home />
		<Projects />
	</main>
{/if}
