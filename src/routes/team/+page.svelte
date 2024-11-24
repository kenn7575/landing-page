<script lang="ts">
	import type { PageData } from './$types';

	import Kenni from '$lib/img/kenniK.webp';
	import Marcus from '$lib/img/marcus.webp';

	import Kasper from '$lib/img/kasper.webp';
	import Nima from '$lib/img/nima.webp';
	import Malthe from '$lib/img/malthe.webp';

	export let data: PageData;
</script>

<svelte:head>
	<title>About SeeMatch - Meet the Team Behind the Magic</title>
	<meta
		name="description"
		content="Get to know the passionate team behind SeeMatch. Learn how our developers, designers, and strategists bring ideas to life to create the ultimate movie night app."
	/>
	<meta property="og:title" content="About SeeMatch - Meet the Team Behind the Magic" />
	<meta
		property="og:description"
		content="Get to know the passionate team behind SeeMatch. Learn how our developers, designers, and strategists bring ideas to life to create the ultimate movie night app."
	/>
	<meta property="og:image" content="/malthe.webp" />
	<meta property="og:image:width" content="480" />
	<meta property="og:image:height" content="480" />
</svelte:head>

<main class="w-full bg-base-300 bg-no-repeat bg-cover bg-center min-h-screen">
	<section class="grid grid-cols-1 gap-16 pt-16 px-4 justify-center">
		<!-- About Section -->
		<article class="col-span-3 row-span-2 border-gradient-outer max-w-4xl w-full mx-auto">
			<div class="border-gradient-inner flex flex-col justify-around gap-4 items-center p-12">
				<div class="flex flex-col gap-8">
					<div>
						<h1 class="text-4xl font-bold">Who are we?</h1>
					</div>
					<p class="max-w-3xl w-full">
						We are a passionate team of software developers with a vision to create an app the world
						truly needs. Our project is currently in the beta stage, and we are working hard to
						refine it for release. We’re looking for beta testers to help us improve! If you’re
						interested, head to the download section and click the link for your platform to get
						started. Your feedback is invaluable in making our app the best it can be, and we deeply
						appreciate your support.
					</p>
				</div>
			</div>
		</article>

		<!-- Team Section -->
		<article
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h2 class="text-2xl font-bold">Kenni Kollemorten</h2>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Web developer</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">UI/UX Designer</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Kenni is a skilled web developer passionate about UI/UX design, ensuring our platforms
							are intuitive and engaging. He oversees user experience across all platforms, crafting
							appealing digital interactions. Kenni also manages our website, social media, and
							marketing, maintaining a consistent brand identity. His work fosters meaningful
							connections with our audience.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class="object-cover" src={Kenni} alt="Kenni, Web Developer" />
						</div>
					</div>
				</div>
			</div>
		</article>
		<article
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h2 class="text-2xl font-bold">Marcus Bager</h2>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Backend developer</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Software Architect</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Marcus is a backend developer and database engineer who builds the infrastructure
							powering our app. He specializes in creating scalable systems to ensure reliable
							performance. Marcus optimizes database functionality and maintains system stability.
							His expertise delivers a seamless, high-quality user experience.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img
								class="object-cover"
								src={Marcus}
								alt="Marcus, Backend Developer"
								loading="lazy"
							/>
						</div>
					</div>
				</div>
			</div>
		</article>
		<article
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h2 class="text-2xl font-bold">Kasper Høg</h2>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Frontend developer</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Software Architect</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Kasper is a frontend app developer who brings our ideas to life with intuitive and
							engaging user interfaces. His keen eye for design ensures our products are visually
							appealing and accessible. Kasper transforms concepts into seamless applications,
							delivering enjoyable user experiences. His dedication is key to achieving our
							company's vision.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img
								class="mix-blend-screen object-cover"
								src={Kasper}
								alt="Kasper, Frontend Developer"
								loading="lazy"
							/>
						</div>
					</div>
				</div>
			</div>
		</article>
		<article
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h2 class="text-2xl font-bold">Malthe Simmonsen</h2>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Product manager</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">COO</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Malthe plays a key role in overseeing operations and shaping our app's ideas. His
							strategic planning and innovative mindset ensure projects run smoothly and align with
							our vision. Malthe's leadership fosters collaboration and transforms concepts into
							impactful solutions. His dedication drives success and delivers exceptional value to
							our users.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class="object-cover" src={Malthe} alt="Malthe, Product Manager" loading="lazy" />
						</div>
					</div>
				</div>
			</div>
		</article>
		<article
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative mb-8"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h2 class="text-2xl font-bold">Nima Badiei</h2>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Web developer</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Full stack Developer</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Nima Badiei is a versatile frontend developer who also supports backend and web
							development. His adaptability ensures our applications are visually engaging and
							robust. With strong technical skills, Nima plays a key role in bringing ideas to life.
							His expertise helps us deliver exceptional, high-quality solutions.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class=" object-cover" src={Nima} alt="Nima, Web Developer" loading="lazy" />
						</div>
					</div>
				</div>
			</div>
		</article>
	</section>
</main>
