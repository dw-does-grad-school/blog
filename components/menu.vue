<template>
    <nav class="font-mono">
        <ul class="flex space-x-4">
            <li>
                <NuxtLink to="/" class="link">Home</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about" class="link">About</NuxtLink>
            </li>
        <li>
            <NuxtLink to="/blog" class="link">Blog</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/projects" class="link">Projects</NuxtLink>
        </li>
    </ul>
    </nav>
</template>

<style scoped>
.link {
    @apply hover:bg-slate-200 p-2;
}
</style>