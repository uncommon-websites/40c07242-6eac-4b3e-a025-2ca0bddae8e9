<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Fehler {page.status}</h1>
	<p>{page.error?.message ?? "Es ist ein Fehler aufgetreten."}</p>
	<a href="/">Zurück zur Startseite</a>
</main>
