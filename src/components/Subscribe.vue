<template>
    <div class="block lg:flex justify-between ">
        <h1 class="hind flex-start font-bold text-[40px] relative  leading-[48px] tracking-[-1px] dark">Company Newsletter</h1>
            <div class="block md:flex gap-[30px]" >
                <div>
                    <input  type="text" v-model="email" @blur="validateEmail"  class="  mt-[15px] lg:mt-0 w-fu lg:w-[286px]  h-[48px] pl-[16px] lg:ml-[-100px] border-solid border-[1px] border-slate-200 rounded-md" placeholder="Your Email">
                    <p v-if="errorMessage" class="pt-2 pr-10 translate-x-[0px] lg:translate-x-[-100px] text-sm text-red-600">{{ errorMessage }}</p>
                </div>
                <button type="submit" class="w-[154px] h-[48px] mt-[15px] lg:mt-0 bg-red-400 hover:bg-red-500 text-white hind-siliguti font-bold text-base tracking-[1px] rounded-md uppercase">
                    Subscribe
                </button>
            </div>
        </div>
</template>

<script>
export default {
  data() {
    return {
      email: "",
      errorMessage: "",
    };
  },
  methods: {
    validateEmail() {
      const regex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
      if (!this.email) {
        this.errorMessage = "Email is required";
      } else if (!regex.test(this.email)) {
        this.errorMessage = "Please enter a valid email address";
      } else {
        this.errorMessage = "";
      }
    },
  },
};
</script>

<style>
.hind-siliguri{
    font-family:'Hind Siliguri', sans-serif;
}
.hind{
    font-family: 'Hind Siliguri', sans-serif;
}

</style>