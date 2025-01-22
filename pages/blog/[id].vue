<template>
    <div>
        <h1>blog entry page</h1>
        <p>blog entry id: {{ id }}</p>
    </div>
</template>

<script setup>
const route = useRoute();
const { id } = route.params;
</script>