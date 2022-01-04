<script setup lang="ts">
import TestWorld from "@/components/TestWorld.vue";

defineProps<{ msg: string }>()
</script>

<template>
  <h1>{{ msg }}</h1>
	<TestWorld/>
</template>
