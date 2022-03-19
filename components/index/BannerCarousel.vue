<template>
  <section>
		<VueSlickCarousel v-bind="settings">
			<div>
				<img src="" alt="">
			</div>
		</VueSlickCarousel>
	</section>
</template>

<script>
	import VueSlickCarousel from 'vue-slick-carousel'
	export default {
		components: {
			VueSlickCarousel
		},
		data(){
			return{
				settings: {
					"dots": true,
					"dotsClass": "slick-dots custom-dot-class",
					"edgeFriction": 0.35,
					"infinite": false,
					"speed": 500,
					"slidesToShow": 1,
					"slidesToScroll": 1
				}
			}
		}
	}
</script>

<style lang="scss" scoped>

</style>