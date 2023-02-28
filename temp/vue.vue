<template>$emit('selected', {})</template>

<script setup>
	const props = defineProps({
		name: {
			type: String,
			default: '',
		},
	});
</script>
