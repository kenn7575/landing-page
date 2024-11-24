<script lang="ts">
</script>

<svelte:head>
	<title>SeeMatch Support - We're Here to Help</title>
	<meta
		name="description"
		content="Need assistance with SeeMatch? Contact us via email or phone for quick support. We're available Mon-Fri, 09:00 - 15:00, to help make your experience seamless."
	/>
	<meta property="og:title" content="SeeMatch Support - We're Here to Help" />
	<meta
		property="og:description"
		content="Need assistance with SeeMatch? Contact us via email or phone for quick support. We're available Mon-Fri, 09:00 - 15:00, to help make your experience seamless."
	/>
	<meta property="og:url" content="https://instamatch.dk/support" />
	<meta property="og:image" content="/seematch-icon.webp" />
	<meta property="og:image:width" content="867" />
	<meta property="og:image:height" content="867" />
</svelte:head>

<main class="px-4 lg:px-32 pt-8">
	<h1 class="text-3xl font-bold text-center mb-8">Welcome to SeeMatch Support</h1>
	<p class="text-center mb-12">
		We're here to help you with any questions or issues. Choose your preferred way to contact us
		below.
	</p>

	<section class="g w-full grid gap-4">
		<!-- <div class="card bg-neutral text-neutral-content shadow-xl">
			<div class="card-body">
				<h2 class="card-title text-primary">Q & A</h2>
				<p>Frequenly asked questions.</p>
				<div class="card-actions justify-end">
					<button class="btn btn-primary btn-outline">Visit</button>
				</div>
			</div>
		</div> -->

		<!-- Support Email Card -->
		<article class="card bg-neutral text-neutral-content shadow-xl">
			<div class="card-body">
				<h2 class="card-title text-primary">Support e-mail</h2>
				<p>In need of support? <br /> Send us a email.</p>
				<div class="card-actions justify-end">
					<a
						href="mailto:info@instamatch.dk"
						aria-label="Send us an email at info@instamatch.dk"
						class="btn btn-outline btn-primary">Contact us</a
					>
				</div>
			</div>
		</article>

		<!-- Call Us Card -->
		<article class="card bg-neutral text-neutral-content shadow-xl">
			<div class="card-body">
				<h2 class="card-title text-primary">Call us</h2>
				<p>
					If you wish to speak to us. You can call us at this number. <br />
					<strong>Mon-Fri: 09:00 - 15:00</strong>
				</p>
				<div class="card-actions justify-end">
					<a
						href="tel:004553805027"
						aria-label="Call us at +45 5380 5027"
						class="btn btn-outline btn-primary">Call</a
					>
				</div>
			</div>
		</article>
		<!-- <div class="card bg-neutral text-neutral-content shadow-xl">
			<div class="card-body">
				<h2 class="card-title">Privacy policy</h2>
				<p>How to process and manage your data.</p>
				<div class="card-actions justify-end">
					<a href="mailto:info@instamatch.dk" class="btn btn-outline btn-primary">Read</a>
				</div>
			</div>
		</div> -->
	</section>
</main>

<style>
	.g {
		grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
	}
</style>
