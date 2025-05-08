<template>
    <div class=" xl:max-w-9/12 mx-auto flex flex-col  py-20 px-6">
        <div class="w-full flex flex-col justify-center items-center gap-10">
            <h2 class="text-4xl font-medium">Choose Your Plan</h2>
            <p class="text-center text-[#4F5665]">Let's choose the package that is best for you and explore it happily and <br> cheerfully.</p>
        </div>
        <div class="py-10 grid xl:grid-cols-3 sm:grid-cols-2 grid-cols-1 w-full lg:gap-30 gap-10 transition-all ">
            <!-- Free -->
            <div class=" p-10 flex flex-col justify-between items-center gap-10 duration-500 bg-white group border-[#DDDDDD] hover:border-[#F53855] border-[2px] rounded-xl ">
                <div class="flex flex-col justify-center items-center gap-10">
                    <img src="../assets/img/svg/Free.svg" alt="">
                <h3 class="font-medium text-xl">Free Plan</h3>
                <ul class="text-sm text-[#4F5665] flex flex-col gap-5">
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Unlimited Bandwitch</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Encrypted Connection</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">No Traffic Logs</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Works on All Devices</li>
                </ul>
                </div>
                
                <div class="flex flex-col justify-center items-center gap-5 mt-20">
                    <span class="font-medium text-2xl">Free</span>
                    <button class="font-medium text-[#F53855] border-[1px] border-[#F53855] group-hover:text-white group-hover:bg-[#F53855] group-hover:shadow-2xl group-hover:shadow-[#F53838] rounded-4xl px-11 py-2 cursor-pointer duration-500">Select</button>
                </div>
            </div>
            <!-- Standard -->
            <div class=" p-10 flex flex-col justify-between items-center gap-10 duration-500 bg-white group border-[#DDDDDD] hover:border-[#F53855] border-[2px] rounded-xl">
                <div class="flex flex-col justify-center items-center gap-10">
                    <img src="../assets/img/svg/Standard.svg" alt="">
                <h3 class="font-medium text-xl">Standard Plan</h3>
                <ul class="text-sm text-[#4F5665] flex flex-col gap-5">
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Unlimited Bandwitch</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Encrypted Connection</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Yes Traffic Logs</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Works on All Devices</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Connect Anyware</li>
                </ul>
                </div>
                <div class="flex flex-col justify-center items-center gap-5 mt-20">
                    <span class="font-medium text-2xl">$9 <span class="font-normal">/ mo</span> </span>
                    <button class="font-medium text-[#F53855] border-[1px] border-[#F53855] group-hover:text-white group-hover:bg-[#F53855] group-hover:shadow-2xl group-hover:shadow-[#F53838] rounded-4xl px-11 py-2 cursor-pointer duration-500">Select</button>
                </div>
            </div>
            <!-- Premium -->
            <div class=" p-10 flex flex-col justify-between items-center gap-10 duration-500 bg-white group border-[#DDDDDD] hover:border-[#F53855] border-[2px] rounded-xl">
                <div class="flex flex-col justify-center items-center gap-10 ">
                    <img src="../assets/img/svg/Premium.svg" alt="">
                <h3 class="font-medium text-xl">Premium Plan</h3>
                <ul class="text-sm text-[#4F5665] flex flex-col gap-5">
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Unlimited Bandwitch</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Encrypted Connection</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">No Traffic Logs</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Works on All Devices</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Connect Anyware</li>
                    <li class="flex gap-4"><img src="../assets/img/svg/Vector (2).svg" alt="">Get New Features</li>
                </ul>
                </div>
                <div class="flex flex-col justify-center items-center gap-5 mt-20">
                    <span class="font-medium text-2xl">$12 <span class="font-normal"> / mo</span></span>
                    <button class=" font-medium text-[#F53855] border-[1px] border-[#F53855] group-hover:text-white group-hover:bg-[#F53855] group-hover:shadow-2xl group-hover:shadow-[#F53838] rounded-4xl px-11 py-2 cursor-pointer duration-500">Select</button>
                </div>
            </div>
        </div>
    </div>
</template>