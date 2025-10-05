<script setup lang="ts">
import { useAuthStore } from '../stores/authStore'

const storeValue = useAuthStore
</script>

<template>
	<span>HomeView</span>

	<RouterLink to="/login">aboba</RouterLink>
</template>
