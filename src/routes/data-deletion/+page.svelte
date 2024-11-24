<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;
</script>

<svelte:head>
	<title>Data Deletion Policy - InstaMatch</title>
	<meta
		name="description"
		content="Read InstaMatch's Data Deletion Policy. Learn how we handle your data and how to request deletion. View the policy or download the PDF."
	/>
	<meta property="og:title" content="Data Deletion Policy - InstaMatch" />
	<meta
		property="og:description"
		content="Understand InstaMatch's Data Deletion Policy. Learn how we handle your data and how to request deletion. View or download the policy."
	/>
	<meta property="og:url" content="https://instamatch.dk/data-deletion" />
	<meta property="og:image" content="/seematch-icon.webp" />
	<meta property="og:image:width" content="867" />
	<meta property="og:image:height" content="867" />
</svelte:head>

<main>
	<iframe
		title="Data Deletion Policy"
		class="w-full min-h-view"
		src="https://docs.google.com/gview?url=https://instamatch.dk/data-deletion.pdf&embedded=true"
		frameborder="0"
		allowfullscreen
	/>
	<p class="text-center mt-4">
		Can't view the document? <a
			href="https://instamatch.dk/data-deletion.pdf"
			target="_blank"
			rel="noopener noreferrer"
			class="text-primary underline">Download the PDF</a
		>.
	</p>
</main>
