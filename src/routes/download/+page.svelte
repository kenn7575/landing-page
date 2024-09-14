<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;

	import appStore from '$lib/img/Pre-order_on_the_App_Store_Badge_US-UK_RGB_wht_121217.svg';
	import googleStore from '$lib/img/PreRegisterOnGooglePlay_Badge_Web_color_en-GB.png';
</script>

<main class="w-full bg-base-100 bg-no-repeat bg-cover bg-center min-h-screen p-8">
	<div class="flex flex-col items-center justify-center pt-32 w-full">
		<div
			class="w-full bg-[url(lib/img/pattern-1.png)] bg-no-repeat bg-cover bg-center min-h-screen"
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
					<a target="_blank" href="https://testflight.apple.com/join/B4InxMpc" class="h-full">
						<img src={appStore} class="object-contain h-full" alt="" />
					</a>
					<a
						target="_blank"
						href="https://play.google.com/store/apps/details?id=com.kasp416h.SeeMatch"
						class="h-full"
					>
						<img src={googleStore} alt="" class="object-contain h-full" />
					</a>
				</div>
			</div>
		</div>
	</div>
</main>
