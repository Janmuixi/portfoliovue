<template>
    <div>
        <div class="flex justify-between flex-wrap items-center gap-10">
            <div class="max-w-[500px]">
                <div class="text-[48px] leading-[48px]">
                    <span class="font-normal">Hello I'am </span>
                    <span class="font-extrabold">Jan Muixi</span><br />
                    <span class="font-extrabold">Frontend </span><span
                        class="text-zinc-500 font-extrabold text-stroke">Developer</span><br />
                    <span class="font-normal">Based in </span><span class="font-extrabold">Spain</span>
                </div>
                <div class="mt-8 text-[16px] text-zinc-200">
                    My name is Jan Muixi and I am a Frontend Developer, I have a solid background in
                    JavaScript and other frontend tools and I am passionate about creating user-centric and
                    visually appealing interfaces.
                </div>
            </div>
            <img class="size-[500px] 2xl:size-[700px]" src="@/assets/images/aboutmepic.svg" alt="aboutmepic" />
        </div>
        <div class="flex flex-col items-center justify-center text-[48px]">
            <div><span class="font-normal">My</span> <span class="font-extrabold">Skills</span></div>
            <div class="mt-10 flex flex-wrap gap-8 justify-center">
                <div v-for="skill in skills" :key="skill.name"
                    class="size-[186px] rounded-[4px] border border-white flex flex-col items-center justify-center gap-8 cursor-pointer hover:bg-gray-800 custom-transition draw-border">
                    <img class="size-[60px]" :src="skill.imgUrl" :alt="skill.name">
                    <div class="text-[20px] font-bold">{{ skill.name }}</div>
                </div>
            </div>

        </div>
    </div>
</template>
<script setup lang="ts">
const skills: { imgUrl: string, name: string }[] = [
    {
        imgUrl: 'https://www.svgrepo.com/show/303206/javascript-logo.svg',
        name: 'JavaScript'
    },
    {
        imgUrl: 'https://www.svgrepo.com/show/374144/typescript.svg',
        name: 'TypeScript'
    },
    {
        imgUrl: 'https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png',
        name: 'Vue.js'
    },
    {
        imgUrl: 'https://www.svgrepo.com/show/374118/tailwind.svg',
        name: 'Tailwind'
    },
    {
        imgUrl: 'https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Sass_Logo_Color.svg/2560px-Sass_Logo_Color.svg.png',
        name: 'Sass'
    },
    {
        imgUrl: 'https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Nuxt_logo.svg/2560px-Nuxt_logo.svg.png',
        name: 'Nuxt'
    }
]
</script>
<style>
.text-stroke {
    text-shadow:
        -1px 0 #fff,
        0 1px #fff,
        1px 0 #fff,
        0 -1px #fff;
}
</style>
