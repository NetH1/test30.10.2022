<template>
    <div class="bg-[#2f3136] max-w-[300px] w-full h-screen wwe">
        <div class="pl-4">
        <div class="text-white flex flex-col  text-left gap-y-6  w-full">
            <div class="relative">
                <div @click="show = !show" class="py-4 pt-[31px] flex justify-between border-b border-b-[#2a2d33] pt-4 hover:text-gray-500en cursor-pointer items-center w-full relative">
                <div><h1 class="text-2xl">Game center</h1></div>
                <div><svg class="fill-white w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M169.4 470.6c12.5 12.5 32.8 12.5 45.3 0l160-160c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L224 370.8 224 64c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 306.7L54.6 265.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l160 160z"/></svg></div>
            </div>
            <div class="relative">
                <ul :class="{'flex':show == false, 'hidden':show == true}" class=" flex-col gap-y-2  cursor-pointer bg-[#18191c] mt-4 py-4 px-4 absolute top-0 right-6 ">
                    <li class="border-b-2 border-b-[#32353b] hover:bg-blue-500">
                        Буст сервера
                    </li>
                    <li class="border-b-2 border-b-[#32353b] hover:bg-blue-500">
                        Пригласить друзей
                    </li>
                    <li class="border-b-2 border-b-[#32353b] hover:bg-blue-500">
                        Настройка сервера
                    </li>
                    <li class="border-b-2 border-b-[#32353b] hover:bg-blue-500">
                        Покинуть сервер
                    </li>
                </ul>
            </div>
            </div>
            <div class="flex flex-col gap-y-6 text-left">
                <div class="cursor-pointer">
                <div @click="show1 =!show1" class="flex items-center hover:text-gray-500 hover:fill-gray-500">
                    <div><svg class="fill-white w-3 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M169.4 470.6c12.5 12.5 32.8 12.5 45.3 0l160-160c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L224 370.8 224 64c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 306.7L54.6 265.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l160 160z"/></svg></div>
                    <div><p class="text-2xl ">Doorbell</p></div>
                </div>
                <ul :class="{'block':show1 == true, 'hidden':show1 == false} ">
                    <li class="py-1 px-2 hover:bg-gray-400 hover:rounded-lg"># welcome</li>
                </ul>
            </div>
            <div class="cursor-pointer">
                <div @click="show2 =!show2" class="flex items-center hover:text-gray-500">
                    <div><svg class="fill-white w-3 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M169.4 470.6c12.5 12.5 32.8 12.5 45.3 0l160-160c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L224 370.8 224 64c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 306.7L54.6 265.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l160 160z"/></svg></div>
                    <div><p class="text-2xl">INFO</p></div>
                </div>
                <ul class=" flex-col gap-y-3" :class="{'flex':show2 == true, 'hidden':show2 == false}">
                    <li class="pt-2 hover:bg-gray-400 hover:rounded-lg py-1 px-2"># rules</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># hello-gootbuy</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># portal</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># feedbaack</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># about</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># ban</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># server</li>
                </ul>
            </div>
            <div class="cursor-pointer">
                <div @click="show3 =!show3" class="flex items-center hover:text-gray-500">
                    <div><svg class="fill-white w-3 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M169.4 470.6c12.5 12.5 32.8 12.5 45.3 0l160-160c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L224 370.8 224 64c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 306.7L54.6 265.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l160 160z"/></svg></div>
                    <div><p class="text-2xl">Lounges</p></div>
                </div>
                <ul class=" flex-col gap-y-3 " :class="{'flex':show3 == true, 'hidden':show3 == false}">
                    <li class="pt-2 hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 1</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 2</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 3</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 4</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># games</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 5</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 6</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 7</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># zone 8</li>
                </ul>
            </div>
            <div class="cursor-pointer">
                <div @click="show4 =!show4" class="flex items-center hover:text-gray-500">
                    <div><svg class="fill-white w-3 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M169.4 470.6c12.5 12.5 32.8 12.5 45.3 0l160-160c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L224 370.8 224 64c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 306.7L54.6 265.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l160 160z"/></svg></div>
                    <div><p class="text-2xl">chat</p></div>
                </div>
                <ul :class="{'flex':show4 == true, 'hidden':show4 == false}" class="flex-col gap-y-3">
                    <li class="pt-2 hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                    <li class="hover:bg-gray-400 hover:rounded-lg py-1 px-2"># chill</li>
                </ul>
            </div>
            </div>
        </div>
    </div>
    <div class="parent ">
                <div class="flex justify-between child items-center bg-gray-700">
                <div class="flex items-center cursor-pointer hover:bg-gray-500 hover:rounded-md px-2 py-2">
                    <img class="w-10 object-cover mr-1" src="../../assets/discord-logo.png" alt="">
                    <div>
                        <p class="text-white text-lg">Egs</p>
                        <p class="text-gray-500">#434fas</p>
                    </div>
                </div>
                <div class="flex items-center w-[90px] gap-x-1 cursor-pointer">
                    <div class="w-[90px] relative"><span :class="{'opacity-0': microphone, 'opacity-100': !microphone}" class="lineoff absolute top-1 left-3 z-20"></span><svg @click="microphone = !microphone" class=" fill-gray-400 px-1 py-2 hover:bg-gray-500 hover:rounded-md" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M192 0C139 0 96 43 96 96V256c0 53 43 96 96 96s96-43 96-96V96c0-53-43-96-96-96zM64 216c0-13.3-10.7-24-24-24s-24 10.7-24 24v40c0 89.1 66.2 162.7 152 174.4V464H120c-13.3 0-24 10.7-24 24s10.7 24 24 24h72 72c13.3 0 24-10.7 24-24s-10.7-24-24-24H216V430.4c85.8-11.7 152-85.3 152-174.4V216c0-13.3-10.7-24-24-24s-24 10.7-24 24v40c0 70.7-57.3 128-128 128s-128-57.3-128-128V216z"/></svg></div>
                    <div class="relative w-[90px]"><span :class="{'opacity-0': headphones, 'opacity-100': !headphones}" class="lineoff absolute top-1 left-3 z-20"></span><svg @click="headphones = !headphones" class="fill-gray-400 px-1 py-2 hover:bg-gray-500 hover:rounded-md " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M256 80C149.9 80 62.4 159.4 49.6 262c9.4-3.8 19.6-6 30.4-6c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48c-44.2 0-80-35.8-80-80V384 336 288C0 146.6 114.6 32 256 32s256 114.6 256 256v48 48 16c0 44.2-35.8 80-80 80c-26.5 0-48-21.5-48-48V304c0-26.5 21.5-48 48-48c10.8 0 21 2.1 30.4 6C449.6 159.4 362.1 80 256 80z"/></svg></div>
                    <div class="w-[90px] relative"><svg class=" fill-gray-400 px-1 py-2 hover:bg-gray-500 hover:rounded-md" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M495.9 166.6c3.2 8.7 .5 18.4-6.4 24.6l-43.3 39.4c1.1 8.3 1.7 16.8 1.7 25.4s-.6 17.1-1.7 25.4l43.3 39.4c6.9 6.2 9.6 15.9 6.4 24.6c-4.4 11.9-9.7 23.3-15.8 34.3l-4.7 8.1c-6.6 11-14 21.4-22.1 31.2c-5.9 7.2-15.7 9.6-24.5 6.8l-55.7-17.7c-13.4 10.3-28.2 18.9-44 25.4l-12.5 57.1c-2 9.1-9 16.3-18.2 17.8c-13.8 2.3-28 3.5-42.5 3.5s-28.7-1.2-42.5-3.5c-9.2-1.5-16.2-8.7-18.2-17.8l-12.5-57.1c-15.8-6.5-30.6-15.1-44-25.4L83.1 425.9c-8.8 2.8-18.6 .3-24.5-6.8c-8.1-9.8-15.5-20.2-22.1-31.2l-4.7-8.1c-6.1-11-11.4-22.4-15.8-34.3c-3.2-8.7-.5-18.4 6.4-24.6l43.3-39.4C64.6 273.1 64 264.6 64 256s.6-17.1 1.7-25.4L22.4 191.2c-6.9-6.2-9.6-15.9-6.4-24.6c4.4-11.9 9.7-23.3 15.8-34.3l4.7-8.1c6.6-11 14-21.4 22.1-31.2c5.9-7.2 15.7-9.6 24.5-6.8l55.7 17.7c13.4-10.3 28.2-18.9 44-25.4l12.5-57.1c2-9.1 9-16.3 18.2-17.8C227.3 1.2 241.5 0 256 0s28.7 1.2 42.5 3.5c9.2 1.5 16.2 8.7 18.2 17.8l12.5 57.1c15.8 6.5 30.6 15.1 44 25.4l55.7-17.7c8.8-2.8 18.6-.3 24.5 6.8c8.1 9.8 15.5 20.2 22.1 31.2l4.7 8.1c6.1 11 11.4 22.4 15.8 34.3zM256 336c44.2 0 80-35.8 80-80s-35.8-80-80-80s-80 35.8-80 80s35.8 80 80 80z"/></svg></div>
                </div>
            </div>
             </div>
    </div>
</template>

<script>
export default {
    data() {
        return{
            show: true,
            show1: true,
            show2: true,
            show3: true,
            show4: true,
            microphone:true, 
            headphones:true,
        }
    }
}
</script>

<style scoped>
.wwe {
    overflow-y: auto;
}
.wwe::-webkit-scrollbar {
  width: 10px;
}

.wwe::-webkit-scrollbar-track {
  border-radius: 10px;
}

.wwe::-webkit-scrollbar-thumb {
  border-radius: 10px;
  background: linear-gradient(180deg, #00c6fb, #005bea);
}
.parent{
    max-width: 300px;
    width: 100%;
    position: relative;
}
.child{
    position: fixed;
    bottom: 0;
    max-width: inherit;
    width: inherit;
}
.lineoff{
    border-left: 3px solid #8693aa;
    height: 35px;
    transform: rotate(130deg);
}

</style>