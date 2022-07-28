<script lang="ts">
	let source: string = "https://www.dropbox.com/s/mnhhzozxwogam3t/me.png?dl=1";
	// let source: string = "";
</script>

<div class="intro w-full h-screen grid place-items-center shadow-xl">
	<div class="lg:container xl:px-8 flex flex-row items-end justify-between">
		<img src={source} alt="me" class="h-screen z-10 object-cover" />
		<div
			class="w-full h-screen hidden lg:flex flex-col justify-center items-end"
		>
			<h1 class="xl:text-9xl lg:text-8xl text-gray-200 font-thin text-right">
				hello, i'm
			</h1>
			<h2
				class="xl:text-7xl lg:text-6xl text-gray-200 font-extralight text-right"
			>
				IAN VRIX DE GUZMAN
			</h2>
			<p class="text-xl text-gray-200 font-light text-right">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam
				necessitatibus maxime quasi possimus repellendus, consectetur nulla cum,
				tempore dolore placeat optio nam illo ratione, molestiae corporis. Qui
				velit sint deleniti.
			</p>
		</div>
	</div>
	<div class="lg:hidden absolute bottom-10 z-20 px-5">
		<h1
			class="text-center text-gray-200 font-thin md:text-8xl sm:text-7xl text-6xl"
		>
			hello, i'm
		</h1>
		<h2
			class="text-center text-gray-200 font-extralight md:text-7xl sm:text-6xl text-5xl"
		>
			IAN VRIX DE GUZMAN
		</h2>
		<p class="text-xl text-gray-200 font-light text-center">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam
			necessitatibus maxime quasi possimus repellendus, consectetur nulla cum,
			tempore dolore placeat optio nam illo ratione, molestiae corporis. Qui
			velit sint deleniti.
		</p>
	</div>
</div>

<style>
	.intro {
		background: rgb(111, 111, 111);
		background: radial-gradient(
			circle,
			rgba(111, 111, 111, 1) 0%,
			rgba(73, 76, 65, 1) 100%
		);
	}
</style>
