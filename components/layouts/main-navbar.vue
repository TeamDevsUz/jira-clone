<template>
    <div class="p-2 h-[10vh] fixed top-0 left-0 right-0 bg-gray-100 dark:bg-gray-900 z-50">
        <div class="container mx-auto flex items-center justify-between">
            <Nuxtlink to="/" class="flex items-center space-x-1">
                <NuxtImg src="/logo.svg" width="50" height="50"/>
                <span class="text-2xl font-medium">Jira software</span>
            </Nuxtlink>

            <div class="flex items-center space-x-2">
                <SharedColorMode/>
                <NuxtLink to="/auth">
                    <UButton 
                    color="blue">Get it free</UButton>
                </NuxtLink>
                <NuxtLink to="/auth">
                    <UButton 
                    color="blue" variant="soft">Sing In</UButton>
                </NuxtLink>
            </div>
        </div>
    </div>
</template>