<template>
<section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-wrap w-full mb-20 flex-col items-center text-center">
      <h1 class="sm:text-3xl text-4xl font-medium title-font mb-2 text-gray-900">Others</h1>
      <p class="lg:w-1/2 w-full leading-relaxed ">統計情報や記事などがまとめてあります</p>
    </div>

    <div class="flex flex-wrap -m-4">

      <div class="xl:w-1/3 md:w-1/2 p-4">
		<NuxtLink to="/articles">
			<div class="border border-gray-200 p-6 rounded-lg">
			<div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
				<svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
				<path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
				</svg>
			</div>
			<h2 class="text-lg text-gray-900 font-medium title-font mb-2">Article</h2>
			<p class="leading-relaxed text-base">
				qiitaやzennの記事がまとめてあります
				<br>
			</p>
			</div>
		</NuxtLink>
      </div>

      <div class="xl:w-1/3 md:w-1/2 p-4">
		<NuxtLink to="/statistics">
			<div class="border border-gray-200 p-6 rounded-lg">
				<div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
					<svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
					<path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2"></path>
					<circle cx="12" cy="7" r="4"></circle>
					</svg>
				</div>
				<h2 class="text-lg text-gray-900 font-medium title-font mb-2">Statistics</h2>
				<p class="leading-relaxed text-base">
					Githubのデータや記事投稿数など統計情報をまとめました
				</p>
			</div>
		</NuxtLink>
      </div>

      <div class="xl:w-1/3 md:w-1/2 p-4">
	  		<a href="https://www.amazon.jp/hz/wishlist/ls/1DTKRI6CNC5IG?ref_=wl_share">
				<div class="border border-gray-200 p-6 rounded-lg">
					<div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
						<svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
						<path d="M21 12.79A9 9 0 1111.21 3 7 7 0 0021 12.79z"></path>
						</svg>
					</div>
					<h2 class="text-lg text-gray-900 font-medium title-font mb-2">My wish list</h2>
					<p class="leading-relaxed text-base">
						技術系の欲しい本がいっぱいあります 📚
						<br><br>
					</p>
				</div>
			</a>
      </div>

      <div class="xl:w-1/3 md:w-1/2 p-4">
	  		<a href="https://mahiro72.hatenablog.com/">
				<div class="border border-gray-200 p-6 rounded-lg">
					<div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 mb-4">
						<svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
						<path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
						</svg>
					</div>
					<h2 class="text-lg text-gray-900 font-medium title-font mb-2">Hatena Blog</h2>
					<p class="leading-relaxed text-base">
						振り返り記事や読書の備忘録を書いています 
						<br><br>
					</p>
				</div>
			</a>
      </div>


    </div>
  </div>
</section>
</template>