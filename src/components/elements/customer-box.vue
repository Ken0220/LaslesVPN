<template>
    <div class="h-full border-[2px] rounded-xl border-[#4F5665]/30 hover:border-red-500 transition-all duration-500 p-5 flex flex-col gap-5 overflow-hidden">
                <div class="flex justify-between items-center p-3 w-full sticky top-0">
                    <div class="flex items-center justify-center gap-5">
                        <img :src="props.imgSrc" alt="" class="rounded-full w-20 h-20">
                        <span class="text-lg font-medium"><slot name="name">Name</slot><br><span class="font-normal text-sm"><slot name="place">City</slot></span></span>
                    </div>
                    <div class="flex">
                        <span class=""><slot name="rating">rating</slot></span>
                        <img src="@/assets/img/svg/Group 1161.svg" alt="" class="">
                    </div>
                </div>
                <div class="overflow-auto whitespace-pre-wrap break-words max-w-full "><p class=""><slot name="comment">comment</slot></p></div>
                
            </div>
</template>
<script lang="ts" setup>
    import { defineProps } from 'vue';

    const props = defineProps({
        imgSrc:{
            type: String,
            default: 'Thisispic'
        }
    })
</script>