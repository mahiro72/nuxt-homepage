<template>
<div>
<section class="text-gray-600 body-font overflow-hidden">
  <div class="container px-5 py-24 mx-auto">
    <div class="-my-8 divide-y-2 divide-gray-100" v-for="(a,a_idx) in articles" :key="a_idx">
		<Article :info="{title: a.title, 
						date:a.date,
						link: a.link,
						description:a.description,
						}"/>
    </div>
  </div>
</section>
</div>
</template>

<script>
import json from '@/assets/data/articles.json';
import Article from '@/components/Article.vue';

export default {
	name:'Articles',
	data(){
		return{
			articles:json.articles,
		}
	}
}
</script>
