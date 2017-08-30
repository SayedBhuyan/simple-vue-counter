<template>
	<div>
		<h2>Smile  :) | You are on Count {{ count }} |</h2>
		<p>
			<button @click="count += 1">Increment</button>
		</p>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				count: 1
			}
		}
	}
</script>