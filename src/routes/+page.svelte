<script>
	import app from '$lib/img/app-iphone.png';
	import app1 from '$lib/img/app1-iphone.png';
	import app2 from '$lib/img/app2-iphone.png';
	import app3 from '$lib/img/app3-iphone.png';
</script>

<div class="grid grid-cols-5 min-h-view">
	<div
		class="bg-pattern1 lg:col-span-3 col-span-5 bg-[url(lib/img/pattern-1.png)] bg-no-repeat bg-cover bg-center"
	>
		<div class="w-full flex h-full justify-center items-center bg-base-100/60 px-8">
			<h1 class="text-5xl font-light leading-tight">
				Movie Picking, Made Magical: <br /> <span class="font-semibold">SeeMatch</span> - Your Shortcut
				to Fun with Friends!
			</h1>
		</div>
	</div>
	<div
		class="hidden col-span-2 bg-[url(lib/img/pattern-2.svg)] bg-no-repeat bg-cover bg-left lg:flex justify-center items-center"
	>
		<img src={app} alt="app preview" class="max-w-xs my-16" />
	</div>
</div>
<!-- Bento grid -->
<div class="grid lg:grid-cols-7 gap-8 p-16 grid-cols-1">
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
</div>
