<template>
    <article class="prose dark:prose-invert prose-pre:bg-white dark:prose-pre:bg-bg-grray-800 prose-pre:text-gray-700 dark:prose-pre:text-gray-300">
        <ContentDoc />
    </article>
</template>

<script setup>
const route = useRoute()
console.log('Current path:', route.path)
</script>