<template>
	<div class="home">
		<div class="container mx-auto px-4 py-6">
			<NavBar class="mt-4" />
			<SiteHeader class="mt-20" />
			<main>
				<About class="mb-48" />
				<div class="flex mb-48">
					<div class="mr-8 px-6">
						<CardHeader
							:is_color="'#34495e'"
							:number="'02'"
							:title1="'how it works'"
							:title2="'Simple and handy rental process'"
						/>
					</div>
					<div class="mr-10">
						<ReadMore
							:body="
                'We believe in using business to drive positive change in the world and nerver sttling for what worked in the past.'
              "
							:btntext="'Learn more about the company'"
							:question="'Interested in our values ?'"
						/>
					</div>
					<div class>
						<ReadMore
							:body="
                'We believe in using business to drive positive change in the world and nerver sttling for what worked in the past.'
              "
							:btntext="'Learn more about the company'"
							:question="'Interested in our values ?'"
						/>
					</div>
				</div>
				<!-- start Section -->
				<div class="flex flex-wrap">
					<div class="w-1/4 p-12">
						<Card
							:title="'text us'"
							:content="
                `text when you want your car.
          No app needed,just an online acount.Real human operators.`
              "
						/>
					</div>

					<div class="w-1/4 p-12 mt-10">
						<Card
							:title="'text us'"
							:content="
                `text when you want your car.
          No app needed,just an online acount.Real human operators.`
              "
						/>
					</div>

					<div class="w-1/4 p-12">
						<Card
							:title="'text us'"
							:content="
                `text when you want your car.
          No app needed,just an online acount.Real human operators.`
              "
						/>
					</div>
					<div class="w-1/4 mt-10 p-12">
						<Card
							:title="'text us'"
							:content="
                `text when you want your car.
          No app needed,just an online acount.Real human operators.`
              "
						/>
					</div>
				</div>
				<!-- End Section -->

				<div class="mt-12 mb-24">
					<Service />
				</div>
				<!-- Start Section Pricing -->
				<Pricing />
				<!-- End Section Pricing  -->
				<!-- Start Section Cars -->
				<div class="section-cars">
					<Cars />
				</div>
				<!-- End Section Cars -->
			</main>
			<Footer />
		</div>
	</div>
</template>
<style>
.section-cars {
	margin-top: 7rem;
}

/* .btn-readmore {
  padding-top: 0.6rem;
  padding-bottom: 0.6rem;
  padding-left: 1rem;
  padding-right: 1rem;
} */
</style>
<script>
// @ is an alias to /src
import CardHeader from "@/components/CardHeader";
import About from "@/components/About";
import ReadMore from "@/components/ReadMore";
import Card from "@/components/Card";
import NavBar from "@/components/NavBar";
import SiteHeader from "@/components/SiteHeader";
import Service from "@/components/Service";
import Pricing from "@/components/Pricing";
import Cars from "@/components/Cars";
import Footer from "@/components/Footer";

export default {
	name: "Home",
	components: {
		NavBar,
		SiteHeader,
		About,
		CardHeader,
		ReadMore,
		Card,
		Service,
		Pricing,
		Cars,
		Footer
	}
};
</script>
