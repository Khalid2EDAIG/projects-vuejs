<style >
.imageFormat {
	width: 29rem;
	height: 39rem;
}
</style>
<template>
	<div id="cars">
		<div class="flex flex-row items-center">
			<img
				src="http://fakeimg.pl/1200x800/95a5a6/fff/?text=the Car"
				class="imageFormat w-1/3 rounded shadow-sm"
			/>
			<div class="py-12 px-48 bg-gray-800">
				<CardHeader
					:is_color="'white'"
					:number="'03'"
					:title1="'service zone'"
					:title2="'We\'ve gotSF covered'"
				/>
				<div>
					<h3 class="mt-4 text-gray-500 text-xl">We provide two delivery options for any trip:</h3>
					<div class="mt-6 flex flex-row items-start text-gray-500">
						<span>
							<i class="fas fa-check"></i>
						</span>
						<div class="ml-8">
							<h1 class="text-white">Conciege service (8 AM - 8 PM daily)</h1>
							<p
								class="mt-6"
							>We deliver or pick up at your doorstep.Always have a parcking sport right out front,just for you.</p>
						</div>
					</div>
					<div class="mt-8 flex flex-row items-start text-gray-500">
						<span>
							<i class="fas fa-check"></i>
						</span>
						<div class="ml-8">
							<h1 class="text-white">Conciege service (8 AM - 8 PM daily)</h1>
							<p
								class="mt-6"
							>We deliver within 3 blocks and unlock it whenever you are ready.Park anywhere legal in our zone, timing.especially for starting early or ending late.</p>
						</div>
					</div>
				</div>
				<ReadMore
					:colorQuestion="'#dfe4ea'"
					:colorBtnText="'white'"
					:btntext="'Learn more about the company'"
					:question="'Interested in our values ?'"
				/>
			</div>
		</div>
	</div>
</template>
<script>
import CardHeader from "./CardHeader";
import ReadMore from "./ReadMore";
export default {
	name: "Cars",
	data() {
		return {};
	},
	props: [],
	components: {
		CardHeader,
		ReadMore
	}
};
</script>

