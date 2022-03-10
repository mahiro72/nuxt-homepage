<template>
	<div>
		<Header />
		<AboutMe />
		<CareerList />
		<ProductList />
		<Skils />
		<ArchiveList />
		<Footer />
	</div>
</template>

<script >
import Header from '@/components/Header.vue';
import AboutMe from '@/components/AboutMe.vue';
import ProductList from '~/components/Product/ProductList.vue';
import Footer from '@/components/Footer.vue';
import ArchiveList from '~/components/Archive/ArchiveList.vue';
import CareerList from '@/components/Career/CareerList.vue'
import Skils from '@/components/Skils.vue'

export default {
  name: 'IndexPage',
  components:{
	  Header,
	  AboutMe,
	  ProductList,
	  Footer,
	  ArchiveList,
	  CareerList,
	  Skils,
  },
}
</script>
