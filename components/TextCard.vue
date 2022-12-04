<script setup lang="ts">
defineProps<{
    text: string;
}>()
</script>

<template>
    <li class="border rounded-lg">
        <h2>{{ text }}</h2>
    </li>
</template>
