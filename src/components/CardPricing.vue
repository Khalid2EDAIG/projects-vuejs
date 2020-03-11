
<template>
	<div id="pricing">
		<!--card 1-->
		<div
			class="mr-6 px-4 py-2 z-10 bg-white rounded border border-gray-400 hover:border-none hover:shadow-2xl hover:z-20 flex flex-col items-center"
		>
			<div class="mb-10">
				<h2 class="mb-4 text-center text-gray-800 font-bold">{{title}}</h2>
				<h4 class="text-center text-gray-600 text-sm">Get {{ number_days }} days/month</h4>
			</div>
			<div class="mb-8">
				<span class="text-4xl font-semibold text-gray-700">${{cout}}</span>
				<span class="text-gray-700">/month</span>
			</div>
			<div class="mb-8 h-1 bg-gray-600 w-64"></div>
			<div class="mb-8 w-1/2 text-center">
				<p>{{content}}</p>
			</div>
			<div>
				<a
					class="block mb-8 text-white bg-gray-600 py-4 px-6 rounded-full focus:shadow-outline hover:bg-gray-700 text-center"
					href
				>Start whit {{title}}</a>
				<a class="block mb-8 py-4 px-6 text-gray-800 text-xl font-semibold hover:text-gray-900" href>
					<span class="mr-2">veiw plan details</span>
					<i class="fas fa-arrow-right"></i>
				</a>
			</div>
		</div>
	</div>
</template>
<script>
//import CardHeader from "./CardHeader";
export default {
	name: "pricing",
	data() {
		return {};
	},
	components: {
		//CardHeader
	},
	props: ["title", "number_days", "cout", "content"]
};
</script>
<style lang='css' scoped>
</style>
