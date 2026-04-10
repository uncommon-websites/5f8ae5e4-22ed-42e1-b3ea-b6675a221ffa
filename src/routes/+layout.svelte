<script lang="ts">
	import "../app.css";
	import Header from "$lib/components/Header.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen flex flex-col font-sans bg-[#fbfbfb] text-gray-900 selection:bg-thoughtful-blue selection:text-white">
	<Header />
	<main class="flex-grow">
		<slot />
	</main>
	<Footer />
</div>
