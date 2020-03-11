<template>
	<div :style="{'color':is_color}">
		<div class="flex flex-row mb-4">
			<span class="mr-8 font-semibold uppercase">
				{{
				number
				}}
			</span>
			<div class="mr-8 mt-2 h-1 bg-gray-700 mr-4 mt-2 w-24"></div>
			<span class="font-semibold uppercase">
				{{
				title1
				}}
			</span>
		</div>
		<h1 class="mb-6 text-3xl font-semibold">{{ title2 }}</h1>
	</div>
</template>
<script>
export default {
	name: "CartHeader",
	data() {
		return {};
	},
	props: ["number", "title1", "title2", "is_color"]
};
</script>
