<template>
    <div class="h-[137px] text-[30px] flex justify-between items-center">
        <div>title</div>
        <div
            class="max-sm:hidden flex justify-center gap-6 md:gap-10 [&>*]:cursor-pointer [&>*]:p-1 [&>*]:px-2 [&>*]:rounded-md [&>*]:transition-all">
            <div class="hover:bg-slate-800">About me</div>
            <div class="hover:bg-slate-800">Skills</div>
            <div class="hover:bg-slate-800">Project</div>
        </div>
        <div class="flex justify-center gap-10 [&>*]:cursor-pointer [&>*]:p-2 [&>*]:rounded-md [&>*]:transition-all">
            <a class="hover:bg-slate-800" href="https://github.com/Janmuixi" target="_blank"><img
                    src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/Git-icon-white.svg/1200px-Git-icon-white.svg.png"
                    alt="github" class="size-8 cursor-pointer" /></a>
            <a class="hover:bg-slate-800" href="https://www.linkedin.com/in/janmuixi/" target="_blank"><img
                    src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/linkedin-app-white-icon.png"
                    alt="linkedin" class="size-8 cursor-pointer" /></a>
        </div>
    </div>
</template>
