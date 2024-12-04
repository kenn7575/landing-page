<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;
</script>

<svelte:head>
	<title>Privacy Policy - InstaMatch</title>
	<meta
		name="description"
		content="View InstaMatch's Privacy Policy to learn how we collect, use, and protect your data. Access the policy online or download the PDF."
	/>
	<meta property="og:title" content="Privacy Policy - InstaMatch" />
	<meta
		property="og:description"
		content="Understand InstaMatch's Privacy Policy. Learn how we handle your data and ensure your privacy is protected."
	/>
	<meta property="og:url" content="https://instamatch.dk/privacy" />
	<meta property="og:image" content="/seematch-icon.webp" />
	<meta property="og:image:width" content="867" />
	<meta property="og:image:height" content="867" />
</svelte:head>

<main>
	<iframe
		title="Privacy Policy"
		class="w-full min-h-view"
		src="https://docs.google.com/gview?url=http://seematch.dk/InstaMatch-privacy-v2.pdf&embedded=true"
		frameborder="0"
		allowfullscreen
	/>
	<p class="text-center mt-4">
		Can't view the document? <a
			href="/InstaMatch-privacy-v2.pdf"
			target="_blank"
			rel="noopener noreferrer"
			class="text-primary underline">Download the PDF</a
		>.
	</p>
</main>
