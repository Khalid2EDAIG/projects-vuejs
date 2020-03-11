<style scoped>
.hoverNavBar:hover {
	border-bottom: 0.25rem solid #2ed573;
}
</style>
<template>
	<div id="NavBar">
		<nav>
			<div class="flex">
				<div class="text-gray-700 text-center py-2">
					<span class="text-3xl text-gray-700 font-semibold">upshift</span>
				</div>
				<div
					class="flex-none sm:flex-1 md:flex-auto lg:flex-initial xl:flex-1 text-gray-700 text-center px-3 py-4"
				>
					<form action="#">
						<input class="mr-3" type="radio" name="personel" value="personel" />
						<label
							class="mr-6 text-xl text-gray-500 hover:text-gray-800 hover:border-t-3 hover:border-gray-700"
						>Personel</label>
						<input class="mr-3" type="radio" name="business" value="business" />
						<label
							class="text-xl text-gray-500 hover:text-gray-800 hover:border-t-3 hover:border-gray-700"
						>Business</label>
					</form>
				</div>
				<div
					class="flex-none sm:flex-1 md:flex-auto lg:flex-initial xl:flex-1 text-xl text-gray-700 text-left px-2 py-4"
				>
					<a
						href="#responsive-header"
						class="block lg:inline-block lg:mt-0 text-gray-500 hover:text-gray-700 hover:font-semibold hoverNavBar mr-6"
					>About</a>
					<a
						href="#responsive-header"
						class="block lg:inline-block lg:mt-0 text-gray-500 hover:text-gray-700 hover:font-semibold hoverNavBar mr-6"
					>Pricing</a>
					<a
						href="#responsive-header"
						class="block lg:inline-block lg:mt-0 text-gray-500 hover:text-gray-700 hover:font-semibold hoverNavBar mr-6"
					>FAQ</a>
					<a
						href="#responsive-header"
						class="block lg:inline-block lg:mt-0 text-gray-500 hover:text-gray-700 hover:font-semibold hoverNavBar mr-4"
					>Contact Us</a>
				</div>
				<div class="flex-none text-gray-700 text-right px-4 py-3">
					<a
						href="#responsive-header"
						class="block lg:inline-block lg:mt-0 text-gray-500 hover:text-gray-700"
					>Log In</a>
					<a
						href="#responsive-header"
						class="block bg-gray-300 ml-3 py-2 px-6 rounded-full lg:inline-block lg:mt-0 text-gray-500 hover:text-gray-700"
					>Join now</a>
				</div>
			</div>
		</nav>
	</div>
</template>
<script>
export default {
	name: "NavBar",
	data() {
		return {};
	},
	methods: {},
	props: {}
};
</script>
