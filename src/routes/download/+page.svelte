<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;

	import appStore from '$lib/img/Pre-order_on_the_App_Store_Badge_US-UK_RGB_wht_121217.svg';
	import googleStore from '$lib/img/PreRegisterOnGooglePlay_Badge_Web_color_en-GB.png';
</script>

<svelte:head>
	<title>Download SeeMatch - Beta Testing Now Available</title>
	<meta
		name="description"
		content="Be among the first to try SeeMatch! Join our beta program and download the app on iOS or Android. Help us refine the ultimate movie night planning app."
	/>
	<meta property="og:title" content="Download SeeMatch - Beta Testing Now Available" />
	<meta
		property="og:description"
		content="Be among the first to try SeeMatch! Join our beta program and download the app on iOS or Android. Help us refine the ultimate movie night planning app."
	/>
	<meta property="og:image" content="/seematch-icon.webp" />
	<meta property="og:image:width" content="867" />
	<meta property="og:image:height" content="867" />
</svelte:head>

<main class="w-full bg-base-100 bg-no-repeat bg-cover bg-center min-h-screen p-8">
	<section class="flex flex-col items-center justify-center pt-32 w-full">
		<div
			class="w-full bg-[url(lib/img/pattern-1.webp)] bg-no-repeat bg-cover bg-center min-h-screen"
		>
			<div class="flex flex-col gap-8 items-center">
				<h1 class="text-4xl font-bold">Help us test the app</h1>
				<p class="max-w-xl leading-relaxed">
					We are thrilled to announce that our app is finally in beta, and we invite you to be among
					the first to experience it. Download the app now and help us bring our ideas to life. Your
					feedback is invaluable in making our services robust and delivering the best experience
					possible. Become a part of our journey and let’s create something amazing together!
				</p>

				<div class="h-12 flex gap-8 w-fit items-center">
					<a
						target="_blank"
						href="https://testflight.apple.com/join/B4InxMpc"
						aria-label="Download on the App Store (TestFlight)"
						class="h-full"
					>
						<img
							src={appStore}
							alt="Pre-order on the App Store badge"
							class="object-contain h-full"
						/>
					</a>
					<a
						target="_blank"
						href="https://play.google.com/store/apps/details?id=com.kasp416h.SeeMatch"
						class="h-full"
						aria-label="Pre-register on Google Play"
					>
						<img
							src={googleStore}
							alt="Pre-register on Google Play badge"
							class="object-contain h-full"
						/>
					</a>
				</div>
			</div>
		</div>
	</section>
</main>
