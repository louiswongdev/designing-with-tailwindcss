<template>
  <header class="bg-gray-900 sm:flex sm:justify-between sm:items-center sm:px-4 sm:py-3">
    <div class="flex items-center justify-between px-4 py-3 sm:py-0">
      <div>
        <img class="h-8" src="/img/logo-inverted.svg" alt="Workcation">
      </div>
      <div class="sm:hidden">
        <button @click="isOpen = !isOpen" type="button" class="block text-gray-500 hover:text-white focus:text-white focus:outline-none">
          <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
            <path v-if="isOpen" fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path>
            <path v-if="!isOpen" fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"/>
          </svg>
        </button>
      </div>
    </div>
    <div :class="isOpen ? 'block' : 'hidden'" class="px-2 pt-2 pb-4 sm:flex sm:p-0">
      <a href="#" class="block px-2 py-1 text-white font-semibold hover:bg-gray-800 rounded">List your property</a>
      <a href="#" class="block mt-1 px-2 py-1 text-white font-semibold hover:bg-gray-800 rounded sm:mt-0 sm:ml-2">Trips</a>
      <a href="#" class="block mt-1 px-2 py-1 text-white font-semibold hover:bg-gray-800 rounded sm:mt-0 sm:ml-2">Messages</a>
    </div>
  </header>
</template>

<script>
  export default {
    data() {
      return {
        isOpen: false,
      }
    }
  }
</script>