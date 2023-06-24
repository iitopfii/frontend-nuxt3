<template>
    <div class="flex w-full h-[60px] bg-slate-700 justify-around items-center px-5">
        <div class="text-white">
            LOGO
        </div>
        <div>
            <ul class="flex gap-5">
                <li class="mx-2">
                    <a href="#" class="text-white">Home</a>
                </li>
                <li class="mx-2">
                    <a href="#" class="text-white">About</a>
                </li>
                <li class="mx-2">
                    <a href="#" class="text-white">Contact</a>
                </li>
            </ul>
        </div>
        <div class="text-white flex items-center gap-4">
            <UAvatar chip-color="primary" src="https://avatars.githubusercontent.com/u/739984?v=4" chip-position="top-right" size="sm" />
            <label>
                :username
            </label>
        </div>
    </div>
</template>