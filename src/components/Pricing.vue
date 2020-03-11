
<template>
	<div id="pricing">
		<div class="flex flex-col items-center">
			<!-- 	<CardHeader
				:number="'02'"
				:title1="'pricing'"
				:title2="'Monthly plans for less than a parcking space.'"
			/>-->
			<div class="flex flex-row mb-4">
				<span class="mr-8 text-gray-700 font-semibold uppercase">04</span>
				<div class="mr-8 mt-2 h-1 bg-gray-700 mr-4 mt-2 w-24"></div>
				<span class="text-gray-700 font-semibold uppercase">Pricing</span>
			</div>
			<h1
				class="mb-6 text-3xl text-gray-900 font-semibold"
			>Monthly plans for less than a parking space.</h1>
			<div class="w-1/2 text-center">
				<p>Plans include concierge delivery and pickup, cleaning and refueling service, full coverage insurance and maintenance-everything but gas and tolls.Join instantly with $0 down and get your car right now.</p>
			</div>
		</div>
		<div class="mt-24 mb-16 flex flex-row">
			<div>
				<CardPricing
					class="pricing-card"
					:title="'Getaway'"
					:number="'4'"
					:cout="'193'"
					:content="'Not sure how much you drive? Get a magic button anytime you need a car.'"
				/>
			</div>
			<div>
				<CardPricing
					class="pricing-card"
					:title="'Getaway'"
					:number="'4'"
					:cout="'219'"
					:content="'Get away up to once a week.Your car is delivered and disppears-like magic.'"
				/>
			</div>
			<div>
				<CardPricing
					class="pricing-card"
					:title="'Freedom'"
					:number="'8'"
					:cout="'389'"
					:content="'Get a car up to twice a week.It\'s feedom whenever you want it \(and no additional fees when you don\'t\).'"
				/>
			</div>
		</div>
	</div>
</template>
<script>
//import CardHeader from "./CardHeader";
import CardPricing from "./CardPricing";
export default {
	name: "pricing",
	data() {
		return {};
	},
	components: {
		CardPricing
	},
	props: []
};
</script>
<style lang='css' scoped>
.pricing-card:hover {
	border-top: 1 solid rgb(32, 32, 32);
	animation-name: pricing-card;
	animation-duration: 2s;
}

@keyframes pricing-card {
	100% {
		margin-top: -3rem;
		margin-bottom: 3rem;
	}
}
</style>
