<template>
	<div class="h-full flex items-start py-5">
		<div class="w-12 flex-shrink-0 flex flex-col text-center leading-none">
			<span class="text-gray-400 pb-2 mb-2 border-b-2 border-gray-200">{{ info.year }}</span>
			<span class="font-medium text-lg text-gray-600 title-font leading-none">{{ info.month }}</span>
		</div>
		<div class="flex-grow pl-6">
			<h2 class="tracking-widest text-xs title-font font-medium text-indigo-200 mb-1">{{ info.category }}</h2>
			<h1 class="title-font text-xl font-medium text-white mb-3">{{ info.title }}</h1>
			<p class="leading-relaxed mb-2">{{ info.description }}</p>
			<a class="text-indigo-400 inline-flex items-center" :href="`${info.link}`">view app
				<svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
					<path d="M5 12h14M12 5l7 7-7 7"></path>
				</svg>
			</a>
		</div>
	</div>
</template>

<script>
export default {
	name:'Product',
	props:{
		info:{
			title:String,
			year:String,
			month:String,
			category:String,
			description:String,
			link:String,
		},
	}
}
</script>