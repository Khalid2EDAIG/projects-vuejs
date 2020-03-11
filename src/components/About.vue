<template>
	<div id="about" class="flex flex-wrap bg-white mt-24 mb-24">
		<div class="w-1/2">
			<div class="bg-black">
				<div class>
					<img src="../assets/images/forest.jpg" alt />
				</div>
			</div>
			<div class="bg-gray-800 p-8 ml-16 body-cart-about">
				<div class="border-l-4 border-gray-600 text-white p-4">
					<p>
						"Since becoming a monthly subscriber,I feel like I hve my car back
						again.It's like I own a car without the worries or cost of keeping
						it around all the time."
					</p>
				</div>
				<div class="m-6 flex flex-wrap items-center">
					<div class="w-1/2 p-4">
						<div class="flex flex-wrap items-center">
							<div class="w-16 h-16 text-white bg-gray-500 rounded-full mr-6">
								<img src="../assets/images/car.jpg" alt class="w-16 h-16 rounded-full" />
							</div>
							<div>
								<span class="text-white text-sm font-semibold">SAM R.</span>
							</div>
						</div>
						<!-- <button
              class="mr-6 text-white rounded-full bg-gray-600 btn-readmore focus:outline-none focus:shadow-outline"
            >
              <i class="fas fa-times fa-2x"></i>
						</button>-->
					</div>
					<div class="w-1/2">
						<div class="text-right text-white">
							<button class="mr-1 hover:text-yellow-500">
								<i class="fas fa-star block"></i>
							</button>
							<button class="mr-1 hover:text-yellow-500">
								<i class="fas fa-star block"></i>
							</button>
							<button class="mr-1 hover:text-yellow-500">
								<i class="fas fa-star block"></i>
							</button>
							<button class="mr-1 hover:text-yellow-500">
								<i class="fas fa-star block"></i>
							</button>
							<button class="mr-1 hover:text-yellow-500">
								<i class="fas fa-star block"></i>
							</button>
							<span class="block mt-2 text-gray-600 text-sm">28 reviews at Yelp</span>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="w-1/2 pl-48">
			<!--  <div class="flex flex-wrap mb-4">
        <div class="mr-4 mb-4">
          <span class="w-1/3 text-gray-500 font-semibold uppercase ">01</span>
        </div>
        <div class="w-1/3 h-1 bg-gray-500 mr-4 mt-2"></div>
        <div>
          <span class="w-1/3 text-gray-500 font-semibold uppercase "
            >About Us</span
          >
        </div>
        <h1 class="mb-6 text-3xl text-gray-900 font-semibold">
          Let's make cities better
        </h1> </div>
			-->
			<CardHeader
				:is_color="'#34495e'"
				:number="'01'"
				:title1="'About Us'"
				:title2="'Let\'s make cities better'"
			/>

			<div class>
				<p class="text-sm text-gray-500 font-medium">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Et dolorem
					distinctio asperiores, recusandae a labore impedit dolor tempore
					possimus officiis quas eius laboriosam quod, necessitatibus voluptatem
					soluta natus. Eligendi, odio?
				</p>
			</div>
			<div class="mt-6">
				<ReadMore
					:body="
            'We believe in using business to drive positive change in the world and nerver sttling for what worked in the past.'
          "
					:btntext="'Learn more about the company'"
					:question="'Interested in our values ?'"
				/>
			</div>
		</div>
	</div>
</template>
<style lang="css" scoped>
.body-cart-about {
	margin-top: -4rem;
	position: relative;
	margin-right: -5rem;
}
</style>
<script>
import CardHeader from "./CardHeader";
import ReadMore from "./ReadMore";
export default {
	name: "About",
	components: {
		ReadMore,
		CardHeader
	},
	data() {
		return {
			//	hover: false
		};
	}
};
</script>
