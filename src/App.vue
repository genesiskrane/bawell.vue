<template>
	<div>
		<p>
			App Name: Loading... <br />
			{{ hostname }}

			Goto Admin To Edit
		</p>
	</div>
</template>

<script setup>
const hostname = window.location.hostname;
</script>
