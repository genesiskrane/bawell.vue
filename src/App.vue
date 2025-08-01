<template>
	{{ hostname }}
	<router-view></router-view>
</template>

<script setup>
const hostname = window.location.hostname;
</script>
