<template>
  <div class="max-w-5xl mx-auto px-4 py-12 md:py-20">
    <div class="flex flex-col md:flex-row items-center md:items-start justify-between">
      <div class="md:max-w-xl">
        <h1 class="font-heebo font-bold mb-2" style="font-family: 'Heebo', sans-serif; font-size: 46px;">
          E aí!👋
        </h1>
        <h2 class="font-heebo font-bold mb-8" style="font-family: 'Heebo', sans-serif; font-size: 46px;">
          Me chamo Daniel, prazer!
        </h2>
        <p class="font-heebo font-normal mb-8" style="font-family: 'Heebo', sans-serif; font-size: 20px;">
          Tenho cinco anos de experiência com desenvolvimento web, e por mais clichê que possa parecer, sou movido pela paixão em solucionar problemas com tecnologia. 
        </p>
        <router-link to="/contato" class="bg-red-400 hover:bg-red-500 text-white font-bold py-3 px-6 rounded-md inline-block">
          Vamos conversar?
        </router-link>
      </div>
      <div class="mt-10 md:mt-0">
        <div class="w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden bg-blue-100">
          <img src="https://placehold.co/400x400/e6f2ff/1170aa?text=Avatar" alt="Profile" class="w-full h-full object-cover">
        </div>
      </div>
    </div>
  </div>
</template>