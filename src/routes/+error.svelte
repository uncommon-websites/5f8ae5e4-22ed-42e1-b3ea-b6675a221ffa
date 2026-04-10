<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Oops – {page.status}</h1>
	<p>{page.error?.message ?? "We couldn't process your request. Please try again."}</p>
	<a href="/">Return to workspace</a>
</main>
