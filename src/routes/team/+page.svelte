<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;
</script>

<main class="w-full bg-base-300 bg-no-repeat bg-cover bg-center min-h-screen">
	<article class="flex py-32 flex-col px-4">
		<h1 class="mx-auto text-5xl">Who are we?</h1>
		<p class="mt-16 max-w-xl mx-auto text-center">
			We are a small team of software developers. We had an idea for an app, that we thoutgh the
			world could really use. We are currently working on the app, and we are hoping to release it
			very soon. We are currently in the beta stage, and we are looking for beta testers. If you are
			interested in beta testing, please contact us via <a
				class="underline"
				href="mailto:info@instamatch.dk">e-mail</a
			>. We aprichiate that you take the time to help us improve our app.
		</p>
	</article>

	<div class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-fit">
		<div class="border-gradient-inner flex flex-col justify-around gap-4 items-center p-12">
			<div class="flex flex-col gap-8">
				<div>
					<h2>Who are we?</h2>
				</div>
				<p class="max-w-xl w-2/3">
					We are a small team of software developers. We had an idea for an app, that we thoutgh the
					world could really use. We are currently working on the app, and we are hoping to release
					it very soon. We are currently in the beta stage, and we are looking for beta testers. If
					you are interested in beta testing, please contact us via e-mail. We aprichiate that you
					take the time to help us improve our app.
				</p>
			</div>
		</div>
	</div>
	<div class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-fit">
		<div class="border-gradient-inner flex flex-col justify-around gap-4 items-center p-12">
			<div class="flex flex-col gap-8">
				<div>
					<h3>Kenni Kollemorten</h3>

					<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Web developer</span>
					<span class="mt-2 badge badge-primary bg-primary/50 uppercase">UI/UX Designer</span>
					<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
				</div>
				<p class="max-w-xl w-2/3">
					Expiriensed web developer, with a passion for UI/UX design. Kenni is responsible for the
					companys UI/UX design across all platforms. He is also responsible for the companys
					website as well as the companys social media presence, marketing and website development.
				</p>
			</div>
		</div>
	</div>
</main>
