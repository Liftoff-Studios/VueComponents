<template>
	<div>
		{{foo}}
	</div>
</template>
<script setup>
	import {ref} from "vue"
	let foo = ref("Hello World")
</script>
