<template>
	<div class="bg-blue-900">
		<div class="container px-5 py-24 mx-auto">
			<p class="text-gray-100 text-5xl">Products</p>
			<section class="text-gray-300 body-font">
				<div class="flex flex-wrap" v-for="(p,p_idx) in products" :key="p_idx">
					<Product :info="{title: p.title, 
									year: p.year, 
									month: p.month, 
									category:p.category,
									description: p.description,
									link: p.link
									}"/>
				</div>
			</section>

		</div>
	</div>
</template>

<script>
import json from '@/assets/data/products.json';
import Product from '@/components/Product/Product.vue';

export default {
	name:'ProductList',
	components:{
		Product,
	},
	data(){
		return{
			products: json.products,
		}
	},
}
</script>