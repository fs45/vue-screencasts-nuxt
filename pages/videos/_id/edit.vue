<template>
	<div>
		<h1>
			Editing {{ video.name }}
			<nuxt-link :to='`/videos/${video.id}`'>
				<button>Go back to show</button>
			</nuxt-link>
		</h1>
	</div>
</template>

<script>
	export default {
		props: ['video']
	}
</script>

<style lang="scss" scoped>
	
</style>