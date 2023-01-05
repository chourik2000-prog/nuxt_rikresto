<template>
    <div>
        <div class="bg-white fixed w-full shadow">
            <navbar class="bg-white flex items-center justify-between">
                <img class="object-contain w-35 h-14" src="tailwind.png" alt="logo de tailwind">
                <div class="flex gap-4">
                    <div class="text-xs col-start-4">
                        <NuxtLink to="/about"><strong>Menu</strong></NuxtLink>
                    </div>
                    <div class="text-xs col-start-4">
                        <NuxtLink to="/about"><strong>Pizza</strong></NuxtLink>
                    </div>
                    <div class="text-xs col-start-4">
                        <NuxtLink to="/about"><strong>Burger</strong></NuxtLink>
                    </div>
                    <div class="text-xs col-start-4">
                        <NuxtLink to="/about"><strong>Riz</strong></NuxtLink>
                    </div>
                    <div class="text-xs col-start-4">
                        <NuxtLink to="/about"><strong>Fufu</strong></NuxtLink>
                    </div>
                    <div class="text-xs col-start-4">
                        <NuxtLink to="/about"><strong>Aloko</strong></NuxtLink>
                    </div>
                </div>
                <div class="flex flex-row pr-8">
                    <img class="object-contain h-4 " src="recherche.png" alt="logo de recherche">
                    <img class="object-contain h-3 " src="panier.jpg" alt="logo de panier">
                </div>
            </navbar>
        </div>
    </div>
</template>