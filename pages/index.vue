<template>
	<div>
		<AboutMe />
		<CareerList />
		<ProductList />
		<Skils />
		<ArchiveList />
	</div>
</template>

<script >

import AboutMe from '@/components/AboutMe.vue';
import ProductList from '~/components/Product/ProductList.vue';
import ArchiveList from '~/components/Archive/ArchiveList.vue';
import CareerList from '@/components/Career/CareerList.vue'
import Skils from '@/components/Skils.vue'

export default {
  name: 'IndexPage',
  components:{
	  AboutMe,
	  ProductList,
	  ArchiveList,
	  CareerList,
	  Skils,
  },
}
</script>
