<script>
export default {
    data() {
        return {
            navbarMenu: false
        }
    },
    methods: {
        toggleMenu() {
            this.navbarMenu = !this.navbarMenu;
        }
    },
    };
</script>

<template>
    <nav  class="flex justify-between w-100 items-center py-6 z-50 relative overflow-hidden">
        <div class="logo w-[200px] -m-3">
            <img class="w-full h-full" src="../../public/img/logo.png" alt="">
        </div>
        <button class="block lg:hidden px-4 py-2 text-white bg-black rounded-md hover:bg-gray-800 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white" v-on:click="toggleMenu()">
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
        </button>
        <ul class="lg:flex gap-7 font-semibold uppercase text-white text-[13px] mr-[72px] hidden">
            <li class="text-[#00CCC6]  hover:cursor-pointer ">
                Inicio
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Nosotros
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Servicios
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Features
            </li>
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                FAQ
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Contacto
            </li> 
        </ul>
    </nav>
    <ul class="absolute left-0 bg-white w-[100vw] z-40 flex flex-col items-center gap-6 p-8 slide-nav" :class="{ 'slide-nav-p': this.navbarMenu }">
            <li class="text-[#00CCC6] hover:cursor-pointer ">
                Inicio
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Nosotros
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Servicios
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Features
            </li>
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                FAQ
            </li> 
            <li class="hover:text-[#00CCC6]  hover:cursor-pointer ">
                Contacto
            </li> 
        </ul>
</template>

<style>
.slide-nav{
    transform: translateY(-500px);
    transition: .5s all;
}
.slide-nav-p{
    transform: translateY(0px);
    transition: .5s all;
}
</style>
