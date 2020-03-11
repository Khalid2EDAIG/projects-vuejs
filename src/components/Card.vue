
<template>
	<div id="card">
		<div class="rounded overflow-hidden flex flex-col items-center">
			<div class="w-16 h-16 text-white bg-gray-500 rounded-full">
				<img src="../assets/images/car.jpg" alt class="w-16 h-16 rounded-full" />
			</div>

			<div class="py-4">
				<div class="font-bold text-xl mb-2 text-center">{{ title }}</div>
				<p class="text-gray-700 text-base text-center">{{ content }}</p>
			</div>
			<div class="bg-gray-300 mt-8 ligne text-center"></div>
		</div>
	</div>
</template>
<script>
export default {
	name: "Card",
	data() {
		return {};
	},
	props: ["title", "content"]
};
</script>
