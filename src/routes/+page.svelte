<script>
	import movieMatch from '$lib/img/moviematch-portrait.webp';
	import discoverSwipe from '$lib/img/discover-swipe.webp';
	import app2 from '$lib/img/app2-iphone.png';
	import app3 from '$lib/img/app3-iphone.png';
</script>

<svelte:head>
	<title>SeeMatch - Plan Movie Nights Effortlessly with Friends</title>
	<meta
		name="description"
		content="Discover SeeMatch, the ultimate app for planning movie nights. Swipe through movies with friends, fine-tune selections to your streaming services, and chat seamlessly. Experience movie picking made magical!"
	/>
	<meta property="og:title" content="SeeMatch - Plan Movie Nights Effortlessly with Friends" />
	<meta
		property="og:description"
		content="Discover SeeMatch, the ultimate app for planning movie nights. Swipe through movies with friends, fine-tune selections to your streaming services, and chat seamlessly. Experience movie picking made magical!"
	/>
	<meta property="og:image" content="/moviematch-portrait.webp" />
	<meta property="og:image:width" content="1419" />
	<meta property="og:image:height" content="2796" />
</svelte:head>

<!-- Hero Section -->
<section class="grid grid-cols-5 min-h-view space-y-8 lg:space-y-0">
	<div
		class="bg-pattern1 lg:col-span-3 col-span-5 bg-[url(lib/img/pattern-1.webp)] bg-no-repeat bg-cover bg-center"
	>
		<div class="w-full flex h-full justify-center items-center bg-base-100/60 px-8">
			<h1 class="text-5xl font-light leading-tight">
				Movie Picking, Made Magical: <br /> <span class="font-semibold">SeeMatch</span> - Your Shortcut
				to Fun with Friends!
			</h1>
		</div>
	</div>
	<div
		class="col-span-5 lg:col-span-2 bg-[url(lib/img/pattern-2.svg)] bg-no-repeat bg-cover bg-left flex justify-center items-center"
	>
		<img
			src={movieMatch}
			alt="SeeMatch app preview showcasing a movie match"
			class="max-w-xs my-16"
		/>
	</div>
</section>

<!-- Bento grid -->
<!-- <section class="grid lg:grid-cols-7 gap-8 p-16 grid-cols-1">
	<div class="bg-base-300 col-span-4 border-gradient-outer">
		<div class="border-gradient-inner">
			<div class="flex justify-between gap-16 items-center p-8">
				<div class="flex flex-col gap-8">
					<h2>Plan the perfect movie night</h2>
					<p>
						SeeMatch is the perfect tool to plan a movie night with your friends. You can create
						groups, invite your friends and swipe through movies together. The algorithm will
						automatically pick movies that you all like. And all you need to do is to swipe through
						them.
					</p>
				</div>
				<img src={app1} class="object-cover object-top max-h-96" alt="app streaming services" />
			</div>
		</div>
	</div>
	<div class="bg-base-300 col-span-3 row-span-2 border-gradient-outer">
		<div class="border-gradient-inner flex flex-col justify-around gap-4 items-center p-12">
			<img
				src={app2}
				class="object-cover object-top max-h-96 lg:w-2/3 my-8 w-1/3"
				alt="app streaming services"
			/>
			<div class="flex flex-col gap-8">
				<h2>Finetune the algorithm to your streaming services</h2>
				<p>
					In a groupe swipe, the algorithm will only pick movies that are available on your, or one
					of your Friends streaming services. This makes it incredibly easy to find movies that you
					can watch without having to rent or buy them.
				</p>
			</div>
		</div>
	</div>
	<div class="bg-base-300 col-span-4 border-gradient-outer">
		<div class="border-gradient-inner">
			<div class="flex justify-between gap-16 items-center p-8">
				<img src={app3} class="object-cover object-top max-h-96" alt="app streaming services" />
				<div class="flex flex-col gap-8">
					<h2>Chat with your friends</h2>
					<p>
						The chat is a great way to discuss the movies you are watching, and its build right into
						the group swipe feature. This makes it easy to share your thoughts and opinions with
						each group member.
					</p>
				</div>
			</div>
		</div>
	</div>
</section> -->

<!-- Features Section -->
<section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-7 gap-8 pt-8 sm:p-16">
	<!-- Feature 1: Plan Movie Night -->
	<article class="bg-base-300 border-gradient-outer col-span-1 md:col-span-2 lg:col-span-4">
		<div class="border-gradient-inner">
			<div class="flex flex-col lg:flex-row justify-between gap-16 items-center p-8">
				<div class="flex flex-col gap-8 order-2 lg:order-none">
					<h2>Plan the perfect movie night</h2>
					<p>
						SeeMatch is the perfect tool to plan a movie night with your friends. You can create
						groups, invite your friends, and swipe through movies together. The algorithm will
						automatically pick movies that you all like. And all you need to do is swipe through
						them.
					</p>
				</div>
				<img
					src={discoverSwipe}
					alt="Discover swipe feature of SeeMatch app"
					loading="lazy"
					class="object-cover object-top max-h-96 w-full sm:px-20 lg:px-0 md:px-52 lg:w-auto"
				/>
			</div>
		</div>
	</article>

	<!-- Feature 2: Finetune Algorithm -->
	<article
		class="bg-base-300 border-gradient-outer col-span-1 md:col-span-2 lg:col-span-3 row-span-1 lg:row-span-2"
	>
		<div class="border-gradient-inner flex flex-col justify-around gap-4 items-center p-12">
			<img
				src={app2}
				loading="lazy"
				alt="Algorithm fine-tuning feature for streaming services on SeeMatch app"
				class="object-cover object-top max-h-96 w-1/2 lg:w-2/3 my-8"
			/>
			<div class="flex flex-col gap-8">
				<h2>Finetune the algorithm to your streaming services</h2>
				<p>
					In a group swipe, the algorithm will only pick movies that are available on your or one of
					your friends' streaming services. This makes it incredibly easy to find movies that you
					can watch without having to rent or buy them.
				</p>
			</div>
		</div>
	</article>

	<!-- Feature 3: Chat with Friends -->
	<article class="bg-base-300 border-gradient-outer col-span-1 md:col-span-2 lg:col-span-4">
		<div class="border-gradient-inner">
			<div class="flex flex-col lg:flex-row justify-between gap-16 items-center p-8">
				<img
					src={app3}
					loading="lazy"
					alt="Chat feature in SeeMatch app for discussing movies"
					class="object-cover object-top max-h-96 order-1 lg:order-none w-full lg:w-auto sm:px-32 md:px-52 lg:px-0"
				/>
				<div class="flex flex-col gap-8 order-2 lg:order-none">
					<h2>Chat with your friends</h2>
					<p>
						The chat is a great way to discuss the movies you are watching, and it's built right
						into the group swipe feature. This makes it easy to share your thoughts and opinions
						with each group member.
					</p>
				</div>
			</div>
		</div>
	</article>
</section>
