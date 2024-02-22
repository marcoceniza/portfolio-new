<template>
    <div class="bg-[#3A3A3A]">
        <div class="wrapper flex justify-center items-center mx-auto h-[700px]">
            <div class="relative">
                <h2 class="text-[40px] font-bold block bg-gradient-to-r from-[#B0FCB0] to-[#12E0F3] bg-clip-text text-transparent relative leading-[100%]">My Works</h2>
                <p class="text-white mt-[40px] mb-[50px] mx-auto w-[600px] max-w-full">Throughout my career as a web developer, I have created several simple sample projects, which I would like to share.</p>
                <div class="flex justify-between gap-4 relative">
                    <figure><img src="../images/main_img2.jpg" alt="CSS 3"></figure>
                    <figure><img src="../images/main_img3.jpg" alt="JavaScript"></figure>
                    <figure><img src="../images/main_img4.jpg" alt="Tailwind CSS"></figure>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
h2:after {content: ''; width: 70px; height: 7px; position: absolute; background: linear-gradient(to right, #B0FCB0, #12E0F3); left: 0; bottom: -25px; right: 0; margin: 0 auto;}
</style>