<template>
    <div class="mx-auto max-w-[1200px] px-6 pb-0 lg:pb-[350px] relative z-20">
        <carousel :items-to-show="1" :transition="700" :wrapAround="true" autoplay="5000" >
            <slide v-for="slide in 3" :key="slide ">
                <div class="shadow-sm hover:shadow-2xl  lg:border-solid lg:border-[1px] lg:border-slate-200 w-[329px] relative top-[100px] lg:top-[50px] h-[448px] rounded-lg bg-white">
                    <div class="member1 w-[297px]  bg-cover bg-no-repeat h-[340px] lg:h-[350] mx-auto lg:mt-[-30px] rounded-br-[50px] relative top-4 rounded-lg bg-red-100">
                        <div class=" hind-siliguri font-bold text-2xl relative top-[360px] dark">Ingo Schimpff</div>
                        <div style="color: rgba(51, 51, 51, 0.496405);" class="text-base  top-[360px] relative work-sans font-normal">
                            Manager
                        </div>
                    </div>
                </div>
                <div class="shadow-sm hover:shadow-2xl  lg:border-solid lg:border-[1px] lg:border-slate-200 hidden relative top-[100px] lg:top-[50px] sm:block w-[329px] h-[448px] rounded-lg bg-white">
                    <div class="member2 w-[297px]   bg-cover bg-no-repeat h-[340px] lg:h-[350] mx-auto lg:mt-[-30px] rounded-br-[50px] relative top-4 rounded-lg bg-red-100">
                        <div class=" hind-siliguri font-bold text-2xl relative top-[360px] dark">Gauthier Drewitt</div>
                        <div style="color: rgba(51, 51, 51, 0.496405);" class="text-base  top-[360px] relative work-sans font-normal">
                            Director
                        </div>
                    </div>
                </div>
                <div class="shadow-sm hover:shadow-2xl  lg:border-solid lg:border-[1px] lg:border-slate-200 hidden md:block relative top-[100px] lg:top-[50px] w-[329px] h-[448px] rounded-lg bg-white">
                    <div class="member3 w-[297px]   bg-cover bg-no-repeat h-[340px] lg:h-[350] mx-auto lg:mt-[-30px] rounded-br-[50px] relative top-4 rounded-lg bg-red-100">
                        <div class=" hind-siliguri font-bold text-2xl relative top-[360px] dark">Winny Rearie</div>
                            <div style="color: rgba(51, 51, 51, 0.496405);" class="text-base  top-[360px] relative work-sans font-normal">
                                Manager
                            </div>
                        </div>
                    </div>
                </slide>
            <template #addons>
            <navigation />
            <pagination />
        </template>
    </carousel>
    </div>
</template>

<script >
import 'vue3-carousel/dist/carousel.css'
import '../assets/member.css'
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel'

export default {
    name: 'App',
    components: {
        Carousel,
        Slide,
        Pagination,
        Navigation,
    },
}
</script>

<style>


</style>