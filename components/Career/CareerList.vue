<template>
	<div class="bg-blue-100">
		<div class="container px-5 py-20 mx-auto">
			<p class="text-gray-600 text-4xl">Careers</p>
			<section class="text-gray-300 body-font">
				<div class="flex flex-wrap" v-for="(c,c_idx) in careers" :key="c_idx">
					<Career :info="{name: c.title, 
									year: c.year, 
									month: c.month, 
									category:c.category,
									description: c.description
									}"/>
				</div>
			</section>

		</div>
	</div>
</template>

<script>
import json from '@/assets/data/careers.json';
import Career from '@/components/Career/Career.vue';

export default {
	name:'CareerList',
	components:{
		Career,
	},
	data(){
		return{
			careers: json.careers,
		}
	},
}
</script>