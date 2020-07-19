<template>
  <div class="h-screen flex flex-col">
    <!-- Header -->
    <header class="flex">
      <!-- User dropdown -->
      <div class="w-64 flex-shrink-0 px-4 py-3 bg-gray-800">
        <button class="w-full flex items-center">
          <img
            class="h-8 w-8 rounded-full object-cover"
            src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=3&w=144&h=144&q=80"
            alt=""
          />
          <span class="ml-4 mr-2 text-sm font-medium text-white">Monica White</span>
          <svg
            class="ml-auto h-5 w-5 stroke-current text-gray-400"
            fill="currentColor"
            viewBox="0 0 20 20"
          >
            <path
              fill-rule="evenodd"
              d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
      </div>
      <!-- Menu Navbar -->
      <div class="flex flex-1 items-center justify-between px-6 bg-gray-700">
        <nav class="flex">
          <a
            href="#"
            class="inline-block px-3 py-2 bg-gray-800 rounded-lg leading-none text-sm font-medium text-white"
            >Mailbox</a
          >
          <a
            href="#"
            class="inline-block ml-2 px-3 py-2 rounded-lg leading-none text-sm font-medium text-white hover:bg-gray-600"
            >Customers</a
          >
          <a
            href="#"
            class="inline-block ml-2 px-3 py-2 rounded-lg leading-none text-sm font-medium text-white hover:bg-gray-600"
            >Reporting</a
          >
          <a
            href="#"
            class="inline-block ml-2 px-3 py-2 rounded-lg leading-none text-sm font-medium text-white hover:bg-gray-600"
            >Manage</a
          >
        </nav>
        <!-- Search + Interactive Icons -->
        <div class="flex items-center">
          <div class="relative w-64">
            <span class="absolute inset-y-0 left-0 flex items-center pl-2">
              <svg
                class="h-5 w-5 fill-current text-gray-500"
                fill="currentColor"
                viewBox="0 0 20 20"
              >
                <path
                  fill-rule="evenodd"
                  d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </span>
            <input
              class="block pl-10 pr-4 py-2 leading-tight w-full bg-gray-900 rounded-lg text-sm placeholder-gray-400 text-white focus:outline-none focus:bg-white focus:placeholder-gray-700 focus:text-gray-900"
              placeholder="Search"
              type="text"
            />
          </div>
          <button class="ml-5 text-gray-400 hover:text-gray-200">
            <svg
              class="h-5 w-5 fill-current"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
              ></path>
            </svg>
          </button>
          <button class="ml-4 text-gray-400 hover:text-gray-200">
            <svg
              class="h-5 w-5 fill-current"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                fill-rule="evenodd"
                d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </button>
        </div>
      </div>
    </header>
    <!-- Sidebar -->
    <div class="w-64 bg-gray-100">

    </div>
    <!-- Main -->
    <main>
      <!-- Inbox Preview Emails -->
      <div></div>
      <!-- Inbox Email Thread -->
      <div></div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {},
  data() {
    return {};
  },
};
</script>

<style src="./assets/tailwind.css"></style>
