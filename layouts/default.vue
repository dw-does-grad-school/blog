<template>
    <div class="container mx-auto max-w-3xl">
        <header class="flex justify-between items-center mt-5">

            <div class="flex items-center space-x-12">
                <div>
                    <NuxtLink to="/" class="text-xl font-semibold p-2 hover:bg-slate-200">Blog Page</NuxtLink>
                </div>

                <Menu />
            </div>
           <ColorModeSelector />
        </header>


        <main class="p-2 mt-10">
            <slot />
        </main>
    </div>
</template>

<script setup>


useHead({
    titleTemplate: '%s | Blog Page', 
    link: [
    {
      rel: 'preconnect',
      href: 'https://fonts.googleapis.com'
    },
    {
      rel: 'stylesheet',
      href: 'https://fonts.googleapis.com/css2?family=Roboto&display=swap',
      crossorigin: ''
    }
  ]
})
</script>

<style>
    body {
        font-family: 'Roboto', sans-serif;
    }
    body{
        @apply bg-white dark:bg-slate-900 text-slate-700 dark:text-slate-700
    }
</style>