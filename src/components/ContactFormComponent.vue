<template>
  <div class="max-w-3xl mx-auto py-12 px-4">
    <h1 class="text-3xl font-bold mb-4 text-center">Vamos conversar?</h1>
    <p class="text-center text-gray-600 mb-8">Nunca digo não pra uma ideia boa ou um café de tarde!</p>
    
    <form class="space-y-6">
      <div>
        <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Como você se chama?</label>
        <input type="text" id="name" name="name" placeholder="Seu nome aqui" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
      </div>
      
      <div>
        <label for="email" class="block text-sm font-medium text-gray-700 mb-1">E o seu email?</label>
        <input type="email" id="email" name="email" placeholder="Pra eu te responder depois" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
      </div>
      
      <div>
        <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Qual é o assunto?</label>
        <input type="text" id="subject" name="subject" placeholder="Do que se trata?" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
      </div>
      
      <div>
        <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Conta tudo aqui</label>
        <textarea id="message" name="message" rows="6" placeholder="Fala sobre sua ideia, projeto ou só manda um oi mesmo..." class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
      </div>
      
      <div>
        <button type="submit" class="w-full bg-red-400 hover:bg-red-500 text-white font-bold py-3 px-6 rounded-md transition duration-300">
          Mandar mensagem
        </button>
      </div>
    </form>
  </div>
</template>

<script setup>
</script> 