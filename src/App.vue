<template>
  <div class="h-screen flex flex-col">
    <!-- Header -->
    <header class="flex flex-shrink-0">
      <!-- User dropdown -->
      <div class="w-64 flex-shrink-0 px-4 py-3 bg-gray-800">
        <button class="w-full flex items-center">
          <img
            class="h-8 w-8 rounded-full object-cover"
            src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=3&w=144&h=144&q=80"
            alt=""
          />
          <span class="ml-4 mr-2 text-sm font-medium text-white"
            >Monica White</span
          >
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
    <div class="flex flex-1 overflow-hidden">
      <div class="w-64 p-6 bg-gray-100 overflow-y-auto">
        <nav>
          <h2
            class="text-xs font-semibold text-gray-600 uppercase tracking-wide"
          >
            Mailboxes
          </h2>
          <div class="mt-3">
            <a
              href="#"
              class="-mx-3 px-3 py-1 flex items-center justify-between text-sm font-medium bg-gray-200 rounded-lg"
            >
              <span class="flex items-center">
                <svg
                  class="h-8 w-8 fill-current text-gray-700"
                  viewBox="0 0 20 20"
                >
                  <path
                    d="M5 3a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2V5a2 2 0 00-2-2H5zm0 2h10v7h-2l-1 2H8l-1-2H5V5z"
                  />
                </svg>
                <span class="ml-2 text-gray-900">Inbox</span>
              </span>
              <span
                class="inline-block px-3 text-center py-1 leading-tight text-xs font-semibold text-gray-700 bg-gray-300 rounded-full"
                >6</span
              >
            </a>
            <a
              href="#"
              class="mt-4 -mx-3 px-3 py-1 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg"
            >
              <span class="flex items-center">
                <svg
                  class="h-8 w-8 fill-current text-gray-500"
                  viewBox="0 0 20 20"
                >
                  <path
                    d="M3 6a3 3 0 013-3h10a1 1 0 01.8 1.6L14.25 8l2.55 3.4A1 1 0 0116 13H6a1 1 0 00-1 1v3a1 1 0 11-2 0V6z"
                  ></path>
                </svg>
                <span class="ml-2 text-gray-700">Flagged</span>
              </span>
            </a>
            <a
              href="#"
              class="mt-4 -mx-3 px-3 py-1 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg"
            >
              <span class="flex items-center">
                <svg
                  class="h-8 w-8 fill-current text-gray-500"
                  viewBox="0 0 20 20"
                >
                  <path
                    d="M17.414 2.586a2 2 0 00-2.828 0L7 10.172V13h2.828l7.586-7.586a2 2 0 000-2.828z"
                  ></path>
                  <path
                    d="M2 6a2 2 0 012-2h4a1 1 0 010 2H4v10h10v-4a1 1 0 112 0v4a2 2 0 01-2 2H4a2 2 0 01-2-2V6z"
                  ></path>
                </svg>
                <span class="ml-2 text-gray-700">Drafts</span>
              </span>
              <span
                class="inline-block px-3 text-center py-1 leading-tight text-xs font-semibold text-gray-700 bg-gray-300 rounded-full"
                >2</span
              >
            </a>
            <a
              href="#"
              class="mt-4 -mx-3 px-3 py-1 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg"
            >
              <span class="flex items-center">
                <svg
                  class="h-8 w-8 fill-current text-gray-500 "
                  viewBox="0 0 20 20"
                >
                  <path
                    d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z"
                  ></path>
                </svg>
                <span class="ml-2 text-gray-700">Assigned</span>
              </span>
              <span
                class="inline-block px-3 text-center py-1 leading-tight text-xs font-semibold text-gray-700 bg-gray-300 rounded-full"
                >1</span
              >
            </a>
            <a
              href="#"
              class="mt-4 -mx-3 px-3 py-1 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg"
            >
              <span class="flex items-center">
                <svg
                  class="h-8 w-8 fill-current text-gray-500"
                  viewBox="0 0 20 20"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span class="ml-2 text-gray-700">Closed</span>
              </span>
            </a>
            <a
              href="#"
              class="mt-4 -mx-3 px-3 py-1 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg"
            >
              <span class="flex items-center">
                <svg
                  class="h-8 w-8 fill-current text-gray-500"
                  viewBox="0 0 20 20"
                >
                  <path
                    fill-rule="evenodd"
                    d="M8.257 3.099c.765-1.36 2.722-1.36 3.486 0l5.58 9.92c.75 1.334-.213 2.98-1.742 2.98H4.42c-1.53 0-2.493-1.646-1.743-2.98l5.58-9.92zM11 13a1 1 0 11-2 0 1 1 0 012 0zm-1-8a1 1 0 00-1 1v3a1 1 0 002 0V6a1 1 0 00-1-1z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span class="ml-2 text-gray-700">Junk</span>
              </span>
            </a>
          </div>

          <h2
            class="mt-8 text-xs font-semibold text-gray-600 uppercase tracking-wide"
          >
            Folders
          </h2>
          <div class="mt-4">
            <a href="#" class="block text-sm font-medium text-gray-700"
              >Refunds</a
            >
            <a href="#" class="mt-4 block text-sm font-medium text-gray-700"
              >Discounts</a
            >
            <a href="#" class="mt-4 block text-sm font-medium text-gray-700"
              >Bugs</a
            >
          </div>
        </nav>
      </div>
      <!-- Main -->
      <main class="bg-gray-200 flex flex-1">
        <!-- Inbox Preview Emails -->
        <div class="flex flex-col w-full max-w-xs flex-grow border-l border-r ">
          <!-- Sort Date row -->
          <div class="flex-shrink-0 px-4 py-2 flex items-center justify-between border-b">
            <button
              class="flex items-center text-xs font-semibold text-gray-600"
            >
              Sort by Date
              <svg
                class="ml-1 h-4 w-4 stroke-current text-gray-500"
                fill="currentColor"
                viewBox="0 0 20 20"
              >
                <path
                  d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </button>
            <button>
              <svg
                class="ml-auto h-5 w-5 stroke-current text-gray-500"
                fill="currentColor"
              >
                <path
                  d="M9.17003 7.40006C9.02003 7.40006 8.86003 7.34006 8.75003 7.22006L6.57006 5.04793V20.4C6.57006 20.73 6.30006 21 5.97006 21C5.64006 21 5.37006 20.73 5.37006 20.4V5.04787L3.19003 7.22006C2.96003 7.46006 2.58003 7.45006 2.34003 7.22006C2.10003 6.99006 2.11003 6.61006 2.34003 6.37006L5.54003 3.17006C5.77003 2.94006 6.15003 2.94006 6.39003 3.17006L9.59003 6.37006C9.82003 6.60006 9.82003 6.98006 9.59003 7.22006C9.48003 7.34006 9.32003 7.40006 9.17003 7.40006ZM21.97 12.5999H9.17001C8.84001 12.5999 8.57001 12.3299 8.57001 11.9999C8.57001 11.6699 8.84001 11.3999 9.17001 11.3999H21.97C22.3 11.3999 22.57 11.6699 22.57 11.9999C22.57 12.3299 22.3 12.5999 21.97 12.5999ZM9.17001 16.8001H17.97C18.3 16.8001 18.57 16.5301 18.57 16.2001C18.57 15.8701 18.3 15.6001 17.97 15.6001H9.17001C8.84001 15.6001 8.57001 15.8701 8.57001 16.2001C8.57001 16.5301 8.84001 16.8001 9.17001 16.8001ZM9.17001 21H13.97C14.3 21 14.57 20.73 14.57 20.4C14.57 20.07 14.3 19.8 13.97 19.8H9.17001C8.84001 19.8 8.57001 20.07 8.57001 20.4C8.57001 20.73 8.84001 21 9.17001 21Z"
                />
              </svg>
              <!-- <svg
                class="ml-auto h-6 w-6 stroke-current text-gray-500"
                fill="currentColor"
                viewBox="0 0 20 20"
              >
                <path
                  d="M3 3a1 1 0 000 2h11a1 1 0 100-2H3zM3 7a1 1 0 000 2h5a1 1 0 000-2H3zM3 11a1 1 0 100 2h4a1 1 0 100-2H3zM13 16a1 1 0 102 0v-5.586l1.293 1.293a1 1 0 001.414-1.414l-3-3a1 1 0 00-1.414 0l-3 3a1 1 0 101.414 1.414L13 10.414V16z"
                ></path>
              </svg> -->
            </button>
          </div>
          <!-- Email preview block -->
          <div class="flex-1 overflow-y-auto">
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900"
                  >Jonathan Maberry</span
                >
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">
                Refund
              </p>
              <p class="mt-2 text-sm text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
                gravida tristique lectus. Nullam in lacus dui...
              </p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900"
                  >Jonathan Maberry</span
                >
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">
                Refund
              </p>
              <p class="mt-2 text-sm text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
                gravida tristique lectus. Nullam in lacus dui...
              </p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900"
                  >Jonathan Maberry</span
                >
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">
                Refund
              </p>
              <p class="mt-2 text-sm text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
                gravida tristique lectus. Nullam in lacus dui...
              </p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900"
                  >Jonathan Maberry</span
                >
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">
                Refund
              </p>
              <p class="mt-2 text-sm text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
                gravida tristique lectus. Nullam in lacus dui...
              </p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900"
                  >Jonathan Maberry</span
                >
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">
                Refund
              </p>
              <p class="mt-2 text-sm text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
                gravida tristique lectus. Nullam in lacus dui...
              </p>
            </a>
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900"
                  >Jonathan Maberry</span
                >
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">
                Refund
              </p>
              <p class="mt-2 text-sm text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
                gravida tristique lectus. Nullam in lacus dui...
              </p>
            </a>
          </div>
        </div>
        <!-- Inbox Email Thread -->
        <div class="flex-1 p-8"></div>
      </main>
    </div>
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
