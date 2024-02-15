<script setup lang="ts">

const aberto = useState('aberto', () => false);

const clickMenu = () => {
    aberto.value = !aberto.value;
}

</script>

<template>
    <nav class="hidden lg:block mt-10">
        <ul>
            <li class="float-left"><img class="block p-2 mr-10" src="~/assets/img/logo.svg" /></li>
            <li class="float-left"><a href="#" class="block p-2 text-gray-500 hover:text-[#2acfcf] font-semibold">Features</a></li>
            <li class="float-left"><a href="#" class="block p-2 text-gray-500 hover:text-[#2acfcf] font-semibold">Pricing</a></li>
            <li class="float-left"><a href="#" class="block p-2 text-gray-500 hover:text-[#2acfcf] font-semibold">Resources</a></li>
            <li class="float-right"><a href="#" class="block px-4 py-2 font-semibold text-white bg-cyan-400 hover:bg-[#2acfcf] rounded-full">Sign Up</a></li>
            <li class="float-right"><a href="#" class="block p-2 mx-5 text-gray-500 hover:text-[#2acfcf] font-semibold">Login</a></li>
        </ul>
    </nav>

    <nav class="lg:hidden">
        <ul>
            <li class="float-left"><img class="block pt-5 mr-10" src="~/assets/img/logo.svg" /></li>
            <li class="float-right"><BarIconCustom class="block pt-5" @click="clickMenu"></BarIconCustom></li>
        </ul>
    </nav>

    <div v-if="aberto" class="text-center text-white p-5 w-[90%] absolute top-16 rounded-lg bg-[#3b3054]">
        <a href="#" class="block p-2 text-xl font-semibold hover:text-[#2acfcf]">Features</a>
        <a href="#" class="block p-2 text-xl font-semibold hover:text-[#2acfcf]">Pricing</a>
        <a href="#" class="block p-2 text-xl font-semibold hover:text-[#2acfcf]">Resources</a>
        <hr class="border-x my-2">
        <a href="#" class="block p-2 my-2 mx-5 text-xl font-semibold hover:text-[#2acfcf]">Login</a>
        <a href="#" class="block px-4 py-2 text-xl font-semibold bg-cyan-400 hover:bg-[#2acfcf] rounded-full">Sign Up</a>
    </div>
</template>