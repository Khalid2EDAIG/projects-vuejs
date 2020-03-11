<template>
	<div id="readMore">
		<div class="block text-sm text-gray-500 font-medium">
			<p>
				{{ body }}
				<!--  We believe in using business to drive positive change in the world and
				nerver sttling for what worked in the past.-->
			</p>
		</div>
		<div class="bg-gray-300 h-1 mt-8 ligne"></div>
		<div class="block flex flex-wrap mt-12">
			<div class="w-16 h-16 text-white bg-gray-500 rounded-full mr-6">
				<img src="../assets/images/car.jpg" alt class="w-16 h-16 rounded-full" />
			</div>

			<div class>
				<span class="block text-sm" :style="{'color':colorQuestion}">{{ question }}</span>
				<button
					v-bind:class="{'block font-semibold focus:outline-none hover:text-gray-900 ':true} "
					:style="{'color':colorBtnText}"
				>
					<span class="mr-2">{{ btntext }}</span>
					<i class="fas fa-arrow-right"></i>
				</button>
			</div>
		</div>
	</div>
</template>
<style scoped></style>
<script>
export default {
	name: "ReadMore",
	data() {
		return {};
	},
	props: [
		"body",
		"btntext",
		"question",
		"color_text",
		"colorBtnText",
		"colorQuestion"
	]
};
</script>
