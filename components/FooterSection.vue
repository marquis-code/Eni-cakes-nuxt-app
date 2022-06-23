<template>
    <div class="bg-pink-500 container mx-auto p-10">
        <div class="flex justify-center items-center space-x-3 md:space-x-1">
            <span class="font-medium text-2xl md:text-sm">COMFY</span>
            <img src="/footerLogo.svg" alt=""/>
            <span class="font-medium text-2xl md:text-sm">CAKES</span>
        </div>
        <div class="flex justify-center items-center space-x-32">
            <div class="space-y-14 md:space-y-10">
                <div class="flex items-center text-white font-sans font-medium space-x-3">
                    <span>icon</span>
                    <span class="text-base text-xs">08097685434, 09078654321</span>
                </div>
                <div class="flex items-center text-white font-sans font-medium space-x-3">
                    <span>icon</span>
                    <span class="text-base text-xs">OLAWALECOMFORT@GMAIL.COM</span>
                </div>
                <div class="flex items-center text-white font-sans font-medium space-x-3">
                    <span>icon</span>
                    <span class="font-light text-base md:text-xs">17,OBANIKORO STREET,LAGOS NIGERIA</span>
                </div>
            </div>
            <div>
                <h1 class="font-semibold font-sans py-5 text-white">WEEKLY NEWSLETTER</h1>
                <form class="space-y-3">
                    <div>
                        <input type="text" v-model="name" placeholder="NAME" class="placeholder-white bg-pink-400 rounded shadow-sm p-4 w-full outline-none border-none ring-1 ring-pink-500 focus:ring-white" />
                    </div>
                    <div>
                        <input type="email" v-model="email" placeholder="EMAIL" class="placeholder-white bg-pink-400 rounded shadow-sm p-4 w-full outline-none border-none ring-1 ring-pink-500 focus:ring-white" />
                    </div>
                    <div>
                        <button class="w-full font-semibold py-3 bg-black text-white">SUBSCRIBE</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>