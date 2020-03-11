
<template>
	<div id="cars">
		<div class="flex flex-row">
			<div class="mr-64 w-1/3">
				<CardHeader
					:is_color="'#34495e'"
					:number="'05'"
					:title1="'the car'"
					:title2="'Always Drive an identical Prius.'"
				/>
				<div>
					<p>
						All our cars are the same so they feel familiar.
						<br />No branding so you don't stic out.
					</p>
					<p>
						Fits comfortably - or a surfboard,bicycle,or skiis.
						<br />54 MPG hubrid gets you to Tahoe and back on a single tank.Phone mount,charging cables,and fasRrak included.Bluetood and safety technology like adaptive cruise control.We use all natural deodorizers and cleaning supplies.
					</p>
				</div>
			</div>
			<div class="w-1/2 mr-8">
				<Carousel />
			</div>
		</div>
	</div>
</template>
<script>
import CardHeader from "./CardHeader";
import Carousel from "./Carousel";
export default {
	name: "Cars",
	data() {
		return {};
	},
	props: [],
	components: {
		CardHeader,
		Carousel
	}
};
</script>

