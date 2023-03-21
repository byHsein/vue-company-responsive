<template>
    <div class="mx-auto my-0 max-w-[1200px] px-6 block relative z-10  lg:flex">  
        <div class="slider mt-[-200px] lg:mt-[-750px]">
            <div class="slides " :style="{ transform }">   
                <div class="slide"> 
                    <div>
                        <div class="lg:mt-[-250px]">
                            <img class="wallet w-20 sm:w-24 sm:h-24 lg:w-32  h-20 lg:h-32 mx-auto relative right-32 sm:right-[175px] lg:right-[230px] top-[420px] lg:top-[590px] z-30 " src="../assets/wallet.png">
                            <div class="yellow mx-auto relative top-[353px] rounded-xl lg:top-[495px] right-[18px] sm:right-[15px]
                            lg:right-[20px] h-[210px] sm:h-[300px] sm:w-[350px] lg:w-[450px] w-[240px] lg:h-[340px] bg-yellow-400"></div>
                            <div class="kotak-merah w-20 sm:w-24 lg:w-36 h-24 sm:h-[125px] lg:h-48 rounded-md top-[265px] sm:top-[240px] lg:top-[320px] mx-auto right-[106px] sm:right-[155px] lg:right-[190px]    bg-red-400 relative z-10 "></div>
                            <div class="refiew sm:h-[340px] sm:w-[350px] bg-cover slate relative w-[260px] lg:w-[450px] 
                            h-[250px] mt-0 sm:mt-[-125px] lg:mt-[-95px] lg:h-[380px] lg:bg-center
                            mx-auto rounded-r-[70px] rounded-br-md rounded-bl-md rounded-tl-md z-20 "></div>
                        </div>
                    </div>
                    <div class="lg:mt-[90px] pl-0 md:pl-0 lg:pl-[100px] xl:pl-[120px]">
                        <div class="flex">
                            <div class="dot-red w-3 h-3 mt-14 lg:mt-60 bg-red-400 rounded-full"></div>
                            <p class="hind-silguri pl-5 mt-[50px] lg:mt-[235px]  font-bold text-rose-400 text-base">Testimonials</p>
                        </div>
                        <h2 class="text-[40px] lg:text-[64px] dark tracking-[-1px] mt-5 font-bold hind-siliguri leading-[48px] lg:leading-[64px]">Reviews</h2>
                        <img class="relative left-[250px] md:left-[650px] lg:left-[370px]" src="../assets/petik.png">
                        <div style="box-shadow: 0px 24px 48px rgba(0, 17, 86, 0.0799083);" class=" pr-[10px] w-[329px] md:w-full lg:w-[42%] h-[288px] lg:h-[220px] mt-[-20px] rounded-lg ">
                            <p style="color: rgba(51, 51, 51, 0.496405);" class="work-sans font-normal text-base leading-8 pt-10 md:pt-[90px] pl-10 lg:pl-8 lg:pt-7 pr-10 lg:pr-9 ">
                                "The sky was cloudless and of a deep dark blue the spectacle before us was indeed sublime sky was cloudless and of a deep dark."
                            </p>
                            <p class=" hind-siliguri font-bold pl-10 lg:pl-8 text-2xl pt-4">Jaroslav Brabec</p>
                            <p style="color: rgba(51, 51, 51, 0.496405);" class="pl-10 lg:pl-8 work-sans font-normal text-sm leading-6">Jaroslav Brabec</p>
                        </div>
                        <div  class="flex gap-2 pt-10 justify-center lg:justify-start">
                            <div class="prev" @click="prevSlide">
                                <img  src="../assets/klik.png">
                                <img class="mt-[-35px] pl-4" src="../assets/left.png">
                            </div>
                            <div @click="nextSlide" class="next md:justify-between">
                                <img src="../assets/klik.png">
                                <img class="mt-[-35px] pl-5" src="../assets/right.png">
                            </div>
                        </div>
                    </div>
                </div>  
                <div class="slide"> 
                    <div>
                        <div class="lg:mt-[-250px]">
                            <img class="wallet w-20 sm:w-24 sm:h-24 lg:w-32  h-20 lg:h-32 mx-auto relative right-32 sm:right-[175px] lg:right-[230px] top-[420px] lg:top-[590px] z-30 " src="../assets/wallet.png">
                            <div class="yellow mx-auto relative top-[353px] rounded-xl lg:top-[495px] right-[18px] sm:right-[15px]
                            lg:right-[20px] h-[210px] sm:h-[300px] sm:w-[350px] lg:w-[450px] w-[240px] lg:h-[340px] bg-yellow-400"></div>
                            <div class="kotak-merah w-20 sm:w-24 lg:w-36 h-24 sm:h-[125px] lg:h-48 rounded-md top-[265px] sm:top-[240px] lg:top-[320px] mx-auto right-[106px] sm:right-[155px] lg:right-[190px]    bg-red-400 relative z-10 "></div>
                            <div class="refiew2 sm:h-[340px] sm:w-[350px] bg-cover slate relative w-[260px] lg:w-[450px] 
                            h-[250px] mt-0 sm:mt-[-125px] lg:mt-[-95px] lg:h-[380px] lg:bg-center
                            mx-auto rounded-r-[70px] rounded-br-md rounded-bl-md rounded-tl-md z-20 "></div>
                        </div>
                    </div>
                    <div class="lg:mt-[90px] pl-0 md:pl-0 lg:pl-[100px] xl:pl-[120px]">
                        <div class="flex">
                            <div class="dot-red w-3 h-3 mt-14 lg:mt-60 bg-red-400 rounded-full"></div>
                            <p class="hind-silguri pl-5 mt-[50px] lg:mt-[235px]  font-bold text-rose-400 text-base">Testimonials</p>
                        </div>
                        <h2 class="text-[40px] lg:text-[64px] dark tracking-[-1px] mt-5 font-bold hind-siliguri leading-[48px] lg:leading-[64px]">Reviews</h2>
                        <img class="relative left-[250px] md:left-[650px] lg:left-[370px]" src="../assets/petik.png">
                        <div style="box-shadow: 0px 24px 48px rgba(0, 17, 86, 0.0799083);" class="w-[329px] md:w-full lg:w-[42%] h-[288px] lg:h-[220px] mt-[-20px] rounded-lg ">
                            <p style="color: rgba(51, 51, 51, 0.496405);" class="work-sans font-normal text-base leading-8 pt-10 md:pt-[90px] pl-10 lg:pl-8 lg:pt-7 pr-10 lg:pr-9 ">
                                "The sky was cloudless and of a deep dark blue the spectacle before us was indeed sublime sky was cloudless and of a deep dark."
                            </p>
                            <p class=" hind-siliguri font-bold pl-10 lg:pl-8 text-2xl pt-4">Laurence Lynn</p>
                            <p style="color: rgba(51, 51, 51, 0.496405);" class="pl-10 lg:pl-8 work-sans font-normal text-sm leading-6">Jaroslav Brabec</p>
                        </div>
                        <div  class="flex gap-2 pt-10 justify-center lg:justify-start">
                            <div class="prev" @click="prevSlide">
                                <img  src="../assets/klik.png">
                                <img class="mt-[-35px] pl-4" src="../assets/left.png">
                            </div>
                            <div @click="nextSlide" class="next md:justify-between">
                                <img src="../assets/klik.png">
                                <img class="mt-[-35px] pl-5" src="../assets/right.png">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>  
    </div>
    
</template>

<script>
export default {
    name: 'Slider',
    data() {
        return {
        currentSlide: 0,
        };
    },
    computed: {
        transform() {
        return `translateX(-${this.currentSlide * 50}%)`;
        },
    },
    methods: {
        nextSlide() {
        this.currentSlide = (this.currentSlide + 1) % 2;
        },
        prevSlide() {
        this.currentSlide = (this.currentSlide - 1 + 0) % 2;
        },
    },
    
};
</script>

<style>
.refiew{
    background-image: url('../assets/review.png');
}
.refiew2{
    background-image: url('../assets/smile.jpg');
}
.slider {
    height: 120vh;
    overflow: hidden;
}

.slides {
    display: flex;
    height: 100%;
    width: 300%;
    transition: transform 0.7s;
}
.slide {
    flex: 2;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

}

@media screen and (min-width: 375px) {
    .slide{
        display: block;
    }
    .slides{
        width:200%;
    } 
}
@media screen and (min-width: 1024px){
    .slide{
        display: flex;
    }
    .slides{
        width: 320%;
    }
}


</style>