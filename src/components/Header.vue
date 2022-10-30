<template>
    <div class="max-w-[100px] w-full px-4 py-4 bg-[#202225] relative navbar_absolute">
        <div class="flex flex-col items-center gap-y-3 cursor-pointer">
            <div class="flex items-center onhiver w-[60px]">
                <span class="absolute left-0 border-l-4 border-l-white hidden span_clas"><p class="opacity-0">a</p></span>
            <img class=" hover:rounded-2xl hover:bg-white transition_img delay-150 px-1 py-1 rounded-full bg-[#36393F]" src="../assets/discord-logo.png" alt="">
        </div>
        <div class="border-b border-b-white w-full"></div>
        <div class="onhiver w-[60px] flex items-center">
            <span class="absolute left-0 border-l-4 border-l-white hidden span_clas"><p class="opacity-0">a</p></span>
            <img class=" px-1 py-1 hover:rounded-2xl hover:bg-white transition_img delay-150 rounded-full" src="../assets/instagram.png" alt="">
        </div>
        <div class="onhiver w-[60px] flex items-center">
            <span class="absolute left-0 border-l-4 border-l-white hidden span_clas"><p class="opacity-0">a</p></span>
            <img class=" px-1 py-1 hover:rounded-2xl hover:bg-white transition_img delay-150 rounded-full" src="../assets/telegram.png" alt="">
        </div>
        <div class="onhiver flex items-center w-[50px]">
            <span class="absolute left-0 border-l-4 border-l-white hidden span_clas"><p class="opacity-0">a</p></span>
            <svg class=" fill-green-500 bg-[#36393F] px-2 py-2 rounded-full hover:rounded-2xl hover:bg-white transition_img delay-150" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M256 80c0-17.7-14.3-32-32-32s-32 14.3-32 32V224H48c-17.7 0-32 14.3-32 32s14.3 32 32 32H192V432c0 17.7 14.3 32 32 32s32-14.3 32-32V288H400c17.7 0 32-14.3 32-32s-14.3-32-32-32H256V80z"/></svg>
        </div>
        <div class="onhiver flex items-center w-[50px]">
            <span class="absolute left-0 border-l-4 border-l-white hidden span_clas"><p class="opacity-0">a</p></span>
            <svg class=" fill-green-500 bg-[#36393F] px-2 py-2 rounded-full hover:rounded-2xl hover:bg-white transition_img delay-150" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352c79.5 0 144-64.5 144-144s-64.5-144-144-144S64 128.5 64 208s64.5 144 144 144z"/></svg>
        </div>
        </div>
    </div>
</template>

<style scoped>
.navbar_absolute{
    position: relative;
    height: 100vh;
}
.transition_img:hover{
    transition: all 1s;
}
.navbar_absolute::after{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    z-index: 9999;
}
.onhiver:hover .span_clas{
    display: block;
    transition: all .3s;
    transition-delay: inherit;
    transition-timing-function: ease-in;
}
</style>