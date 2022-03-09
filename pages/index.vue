<template>
	<div>
		<Header />
		<AboutMe />
		<ProductList />
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

export default {
  name: 'IndexPage',
  components:{
	  Header,
	  AboutMe,
	  ProductList,
	  Footer,
	  ArchiveList,
  },
}
</script>
