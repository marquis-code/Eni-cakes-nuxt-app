<template>
    <div class="sticky w-full z-20 top-0 bg-pink-600 container mx-auto flex justify-between items-center px-10 py-3 border-b border-white ">
        <div class="flex justify-center items-center">
            <span class="font-bold font-sans text-white text-sm select-none">COMFY</span>
            <img src="/cakeLogo.svg" alt="" class="h-10 w-10 object-contain"/>
            <span class="font-bold font-sans text-white text-sm select-none">CAKES</span>
        </div>
        <div class="hidden md:flex justify-center items-center space-x-10 md:space-x-5">
            <ul v-for="navItem in navList" :key='navItem.name' class="font-sans text-white font-light">
                <nuxt-link :to="navItem.link" class="hover:underline duration-500 font-light select-none">{{navItem.name}}</nuxt-link>
            </ul>
        </div>
        <div class="flex md:hidden">
            <button class="bg-white text-pink-600 text-sm font-sans rounded-full shadow-md py-3 px-5">GET STARTED</button>
        </div>
    </div>
</template>

<script>
export default {
    name : 'NavigationBar',
    data(){
        return {
            navList : [
                {name : 'Home', link : '/#'},
                {name : 'About Us', link : '/#'},
                {name : 'Blog', link : '#'},
                {name : 'Login', link : '/#'},
                {name : 'Register', link : '/#'}
            ]
        }
    }
}
</script>