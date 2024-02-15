<template>
  <div class="bg-white">
    <div class="flex flex-col mx-5 lg:mx-[15%] 2xl:mx-[25%]">
      <Navbar></Navbar>

      <div class="flex flex-col text-center lg:flex-row lg:text-left items-center my-10">
          <div class="flex-initial order-last my-5 lg:order-first">
            <h1 class="text-4xl md:text-6xl font-bold">More than just shorter links</h1>
            <p class="mt-5 mb-10 font-semibold text-lg text-gray-500">Build your brand's recognition and get detailed insights on how your links are performing.</p>
            <button class="py-4 px-10 font-semibold text-white bg-cyan-400 hover:bg-[#2acfcf] rounded-full">Get Started</button>
          </div>
          <div>
            <img class="lg:ml-10" src="~/assets/img/illustration-working.svg"/>
          </div>
      </div>

      <div class="flex justify-center items-center relative translate-y-2/4 rounded-lg bg-[url('~/assets/img/bg-shorten-desktop.svg')] bg-[#6745bd]">
        <div class="flex flex-col lg:flex-row p-5 lg:p-10 w-full">
            <input class="flex-1 w-full p-4 mr-5 mb-5 lg:mb-0 rounded-lg border z-10" placeholder="Shorten a link here..." />
            <button class="py-4 px-6 font-semibold text-white bg-cyan-400 hover:bg-[#2acfcf] rounded-lg">Shorten It!</button>
        </div>
      </div>
    </div>    

    <div class="bg-gray-200">
      <div class="flex flex-col mx-5 text-center lg:mx-[15%] 2xl:mx-[25%]">
        <h1 class="mt-32 font-bold text-4xl">Advanced Statistics</h1>
        <h1 class="text-gray-400 font-semibold my-4 w-auto mx-auto">Track how your links are performing across the web with our advanced statistics dashboard.</h1>

        <div class="grid grid-cols-1 lg:grid-cols-3 gap-10 my-10">
          <div class=" bg-white rounded-lg">
            <img class="absolute translate-y-[-50%] translate-x-[25px] p-3 bg-[#6745bd] rounded-full" src="~/assets/img/icon-brand-recognition.svg"/>
            <div class="mt-5 p-5 pr-10 pb-10 text-left">
              <p class="my-5 text-xl font-bold">Brand Recognition</p>
              <p class="text-gray-400">Boost your brand recognition with each click. Generic links don’t mean a thing. Branded links help instil confidence in your content.</p>
            </div>
          </div>
          <div class=" bg-white rounded-lg">
            <img class="absolute translate-y-[-50%] translate-x-[25px] p-3 bg-[#6745bd] rounded-full" src="~/assets/img/icon-detailed-records.svg"/>
            <div class="mt-5 p-5 pr-10 text-left">
              <p class="my-5 text-xl font-bold">Detailed Records</p>
              <p class="text-gray-400">Gain insights into who is clicking your links. Knowing when and where people engage with your content helps inform better decisions.</p>
            </div>
          </div>
          <div class=" bg-white rounded-lg">
            <img class="absolute translate-y-[-50%] translate-x-[25px] p-3 bg-[#6745bd] rounded-full" src="~/assets/img/icon-fully-customizable.svg"/>
            <div class="mt-5 p-5 pr-10 text-left">
              <p class="my-5 text-xl font-bold">Fully Customizable</p>
              <p class="text-gray-400">Improve brand awareness and content discoverability through customizable links, supercharging audience engagement.</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div>
      <div class="flex flex-col justify-center h-[250px] bg-purple-300">
        <img class="w-full h-[250px] absolute bg-[#6745bd]" src="~/assets/img/bg-boost-desktop.svg"/>
        <div class="z-10 text-white text-center">
          <h1 class="m-5 text-4xl font-bold">Boost your links today</h1>
          <button class="py-4 px-10 font-semibold text-white bg-cyan-400 hover:bg-[#2acfcf] rounded-full">Get Started</button>
        </div>
      </div>
    </div>

    <Footer></Footer>

  </div>
</template>