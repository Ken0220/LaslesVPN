<template>
    <nav>
        <div class=" xl:max-w-9/12 mx-auto flex justify-between items-center py-10 px-5">
            <!-- Logo -->
            <div class="flex items-center gap-2">
                <img src="../assets/img/svg/Vector.svg" alt="">
                <h3 class="text-xl ">Lasles<span class="font-bold ">VPN</span></h3>
            </div>
            <!-- NavbarList -->
            <ul class="hidden gap-10 text-[#4F5665] lg:flex transition-all">
            <li class=" flex flex-col after:content-[''] after:rounded-full after:w-0 hover:after:w-full after:h-[2px] after:bg-[#4F5665] after:duration-500"><a href="!#" class="">About</a></li>
            <li class=" flex flex-col after:content-[''] after:rounded-full after:w-0 hover:after:w-full after:h-[2px] after:bg-[#4F5665] after:duration-500"><a href="!#" class="">Features</a></li>
            <li class=" flex flex-col after:content-[''] after:rounded-full after:w-0 hover:after:w-full after:h-[2px] after:bg-[#4F5665] after:duration-500"><a href="!#" class="">Pricing</a></li>
            <li class=" flex flex-col after:content-[''] after:rounded-full after:w-0 hover:after:w-full after:h-[2px] after:bg-[#4F5665] after:duration-500"><a href="!#" class="">Testimonials</a></li>
            <li class=" flex flex-col after:content-[''] after:rounded-full after:w-0 hover:after:w-full after:h-[2px] after:bg-[#4F5665] after:duration-500"><a href="!#" class="">Help</a></li>
            </ul>
            <!-- Sign In/Up -->
            <div class=" lg:flex gap-5 hidden">
                <button class="font-medium cursor-pointer">Sign In</button>
                <button class="font-medium text-[#F53855] border-[1px] rounded-4xl px-11 py-2 cursor-pointer select">Sign Up</button>
            </div>
            <!-- Burger -->
            <button class="size-8 flex flex-col gap-1 lg:hidden">
                <div class="w-full h-1 bg-[#4F5665]"></div>
                <div class="w-full h-1 bg-[#4F5665]"></div>
                <div class="w-full h-1 bg-[#4F5665]"></div>
             </button>
        </div>
    </nav>
</template>
