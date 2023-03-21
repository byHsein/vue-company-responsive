<template>
    <div class="bg-custom bg-no-repeat relative h-screen bg-right-top z-10">
        <div class="mx-auto my-0 max-w-[1200px] px-6 ">
            <div class="flex justify-between">
                <div class="hind-siligury font-bold text-[40px] w-[81px] h-[48px]">
                    CMP
                </div>
                <nav class="relative w-full hidden md:flex lg:flex flex-wrap items-center justify-between py-5">
                    <ul class="flex work-sans text-base font-semibold">
                        <li class="pl-10 cursor-pointer">About</li>
                        <li class="pl-10 cursor-pointer">Portofolio</li>
                        <li class="pl-10 cursor-pointer">Service</li>
                        <li class="pl-10 cursor-pointer">Blog</li>
                        <li class="pl-10 cursor-pointer">Contact</li>
                    </ul>
                </nav>
                <img class="block md:hidden px-2 py-2 lg:hidden" src="../assets/menu.png">
                <button style="border: 1px solid rgba(240, 117, 102, 0.236809); color: #f07566" class="hidden hover:bg-slate-200 md:block lg:block rounded-md mt-2 hind-siliguri text-base px-8 w-[138px] h-[48px] font-bold">
                    CONTACT
                </button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Navbar'
};
</script>

<style>
.bg-custom{
    background-image:url('../assets/Rectangle.png');
    
}
</style>
