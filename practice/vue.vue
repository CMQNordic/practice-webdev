<script setup>
	const id = ref('1');

	const fnc = () => {
		return id.value;
	};

	const com = computed(() => {
		return id.value;
	});
</script>
