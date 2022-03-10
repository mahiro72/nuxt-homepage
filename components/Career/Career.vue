<template>
	<div class="h-full flex items-start py-5">
		<div class="w-12 flex-shrink-0 flex flex-col text-center leading-none">
			<span class="text-gray-500 pb-2 mb-2 border-b-2 border-gray-400">{{ info.year }}</span>
			<span class="font-medium text-lg text-gray-600 title-font leading-none">{{ info.month }}</span>
		</div>
		<div class="flex-grow pl-6">
			<h2 class="tracking-widest text-xs title-font font-medium text-indigo-600 mb-1">{{ info.category }}</h2>
			<h1 class="title-font text-xl font-medium text-white mb-3">{{ info.title }}</h1>
			<p class="leading-relaxed text-gray-600 mb-2">{{ info.description }}</p>
		</div>
	</div>
</template>

<script>
export default {
	name:'Career',
	props:{
		info:{
			name:String,
			year:String,
			month:String,
			category:String,
			description:String,
		},
	}
}
</script>