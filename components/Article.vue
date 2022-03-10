<template>
<div class="py-8">
	<p class="mt-1 text-gray-500 text-sm">{{ info.date }}</p>
	<div class=" flex flex-wrap md:flex-nowrap">
		
		<!-- <div class="md:w-64 md:mb-0 mb-6">
			<span class="mt-1 text-gray-500 text-sm">{{ info.date }}</span>
		</div> -->
		<div class="md:flex-grow">
			<h2 class="text-xl font-medium text-gray-900 title-font mb-2">
				{{ info.title }}
			</h2>
			<p class="leading-relaxed">
				{{ info.description }}
			</p>
			<a class="text-indigo-500 inline-flex items-center mt-4" :href="`${info.link}`"> view 
			<svg class="w-4 h-4 ml-2" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
				<path d="M5 12h14"></path>
				<path d="M12 5l7 7-7 7"></path>
			</svg>
			</a>
		</div>
	</div>
</div>

</template>

<script>
export default {
	name:'Article',
	props:{
		info:{
			title:String,
			date:String,
			link:String,
			description:String,
		}
	}
}
</script>