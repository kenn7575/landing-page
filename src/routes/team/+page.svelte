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
	<div class="grid grid-cols-1 gap-16 pt-16 px-4 justify-center">
		<div class="col-span-3 row-span-2 border-gradient-outer max-w-4xl w-full mx-auto">
			<div class="border-gradient-inner flex flex-col justify-around gap-4 items-center p-12">
				<div class="flex flex-col gap-8">
					<div>
						<h2>Who are we?</h2>
					</div>
					<p class="max-w-3xl w-full">
						We are a small team of software developers. We had an idea for an app, that we thoutgh
						the world could really use. We are currently working on the app, and we are hoping to
						release it very soon. We are currently in the beta stage, and we are looking for beta
						testers. If you are interested in beta testing, please go to the download and press the
						link for your platform to get started. We aprichiate that you take the time to help us
						improve our app.
					</p>
				</div>
			</div>
		</div>
		<div
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h3>Kenni Kollemorten</h3>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Web developer</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">UI/UX Designer</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Kenni is an experienced web developer with a passion for UI/UX design. He brings
							creativity and attention to detail to his role, overseeing the company's user
							interface and experience across all platforms. Dedicated to crafting intuitive and
							engaging digital experiences, Kenni is also responsible for managing the company's
							website, social media presence, and marketing initiatives, ensuring consistent brand
							messaging and meaningful engagement with the audience.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class="object-cover" src={Kenni} alt="Kenni" />
						</div>
					</div>
				</div>
			</div>
		</div>
		<div
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h3>Marcus Bager</h3>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Backend developer</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Software Architect</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Marcus is a dedicated backend app developer and database engineer committed to making
							our applications and services robust and reliable. With a passion for building
							efficient and scalable backend systems, he is responsible for developing the
							infrastructure that powers our app. Marcus ensures that our services deliver the best
							possible experience for our users by maintaining optimal performance and reliability.
							His expertise plays a crucial role in providing seamless and high-quality services,
							contributing significantly to our mission of exceeding user expectations.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class="object-cover" src={Marcus} alt="Marcus" />
						</div>
					</div>
				</div>
			</div>
		</div>
		<div
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h3>Kasper Høg</h3>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Frontend developer</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Software Architect</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Kasper is a talented frontend app developer who plays a pivotal role in bringing our
							ideas to life. With a keen eye for design and a passion for crafting intuitive user
							interfaces, he transforms innovative concepts into engaging and user-friendly
							applications. Kasper's expertise ensures that our products are visually appealing and
							offer seamless experiences, making them accessible and enjoyable for all users. His
							dedication to excellence is vital in delivering high-quality services and realizing
							our company's vision.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class="mix-blend-screen object-cover" src={Kasper} alt="Kasper" />
						</div>
					</div>
				</div>
			</div>
		</div>
		<div
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h3>Malthe Simmonsen</h3>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Product manager</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">COO</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Malthe is a pivotal member of our team who oversees operations and contributes
							significantly to the development of our app's ideas. With a talent for strategic
							planning and a passion for innovation, he ensures that our projects run smoothly and
							align with our collective vision. Malthe's leadership fosters collaboration and
							efficiency, enabling the team to transform concepts into impactful solutions. His
							dedication to excellence and ability to unite diverse perspectives are instrumental in
							driving our company's success and delivering exceptional value to our users.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class="object-cover" src={Malthe} alt="Malthe" />
						</div>
					</div>
				</div>
			</div>
		</div>
		<div
			class="bg-base-300 col-span-3 row-span-2 border-gradient-outer w-full max-w-4xl mx-auto relative mb-8"
		>
			<div class="border-gradient-inner flex flex-col justify-around gap-4 p-12">
				<div class="flex justify-between flex-col sm:flex-row gap-2">
					<div class="flex flex-col gap-8">
						<div>
							<h3>Nima Badiei</h3>

							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Web developer</span>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase"
								>Full stack Developer</span
							>
							<span class="mt-2 badge badge-primary bg-primary/50 uppercase">Co-founder</span>
						</div>

						<p class="max-w-xl sm:w-2/3">
							Nina Badiei is a versatile frontend developer who also contributes to backend and web
							development whenever needed. With a strong skill set across multiple areas of software
							development, she plays a crucial role in bringing our projects to life. Nina's
							adaptability and dedication enable her to seamlessly transition between different
							aspects of development, ensuring our applications are both visually engaging and
							functionally robust. Her collaborative spirit and technical expertise greatly enhance
							our team's ability to deliver high-quality solutions that exceed user expectations.
						</p>
					</div>
					<div class="avatar">
						<div class="w-48 rounded-full my-auto">
							<img class=" object-cover" src={Nima} alt="Nima" />
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</main>
