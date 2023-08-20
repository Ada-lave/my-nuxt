<template>
    <div>
        <nav class="p-6 flex items-center justify-between bg-teal-800">
            <NuxtLink to="/" class="text-xl text-white">YourJob</NuxtLink>

            <div class="flex items-center space-x-4">
                <NuxtLink to="/" class="text-white hover:text-teal-300">Главная</NuxtLink>
                <NuxtLink to="/browse" class="text-white hover:text-teal-300">Browse</NuxtLink>
            </div>
        </nav>

        <slot />

        <footer class="p-6 flex flex-wrap items-center justify-between bg-gray-900">
            <p class="text-gray-300">Copyright (c) 2023 - YourJob</p>

            <div class="flex mt-6 md:mt-0 items-center space-x-4">
                <NuxtLink to="/login" class="py-4 px-6 bg-teal-900 hover:bg-teal-700 rounded-lg text-white">Войти</NuxtLink>
                <NuxtLink to="/login" class="py-4 px-6 bg-teal-900 hover:bg-teal-700 rounded-lg text-white">Зарегистрироваться</NuxtLink>
            </div>
        </footer>

    </div>
</template>