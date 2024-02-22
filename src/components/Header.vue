<template>
    <div class="bg-[#313131]">
        <div class="wrapper flex justify-between items-center mx-auto px-4 min-h-[50px]">
            <a class="text-white cursor-pointer bg-gradient-to-r from-[#B0FCB0] to-[#12E0F3] bg-clip-text text-transparent font-bold text-[22px]" @click="$router.push('/')">MC</a>
            <ul class="flex text-white gap-5">
                <li><a class="cursor-pointer hover:underline" @click="$router.push('/')">HOME</a></li>
                <li><a class="cursor-pointer hover:underline" @click="$router.push('/')">ABOUT</a></li>
                <li><a class="cursor-pointer hover:underline" @click="$router.push('/')">WORKS</a></li>
                <li><a class="cursor-pointer hover:underline" @click="$router.push('/')">RESUME</a></li>
                <li><a class="cursor-pointer hover:underline" @click="$router.push('/')">CONTACT</a></li>
            </ul>
        </div>
    </div>
</template>