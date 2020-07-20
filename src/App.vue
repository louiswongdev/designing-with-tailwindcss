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
          <span class="ml-4 mr-2 text-sm font-normal text-white"
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
                  viewBox="0 0 26 26"
                >
                  <path
                    d="M5 13.397v-9.859c0.44-0.218 1.365-0.538 3-0.538 1.281 0 2.361 0.421 3.629 0.928 1.232 0.493 2.652 1.072 4.371 1.072 1.298 0 2.278-0.175 3-0.397v9.859c-0.44 0.218-1.365 0.538-3 0.538-1.281 0-2.361-0.421-3.629-0.928-1.232-0.493-2.652-1.072-4.371-1.072-1.298 0-2.278 0.175-3 0.397zM5 22v-6.462c0.44-0.218 1.365-0.538 3-0.538 1.281 0 2.361 0.421 3.629 0.928 1.232 0.493 2.652 1.072 4.371 1.072 3.247 0 4.507-1.093 4.707-1.293 0.195-0.195 0.293-0.451 0.293-0.707v-12c0-0.552-0.448-1-1-1-0.265 0-0.506 0.103-0.685 0.272-0.096 0.078-0.984 0.728-3.315 0.728-1.281 0-2.361-0.421-3.629-0.928-1.232-0.493-2.652-1.072-4.371-1.072-3.247 0-4.507 1.093-4.707 1.293-0.195 0.195-0.293 0.451-0.293 0.707v19c0 0.552 0.448 1 1 1s1-0.448 1-1z"
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
                  class=" h-8 w-8 fill-current text-gray-500"
                  viewBox="0 0 28 28"
                >
                  <path
                    d="M11 3h-7c-0.828 0-1.58 0.337-2.121 0.879s-0.879 1.293-0.879 2.121v14c0 0.828 0.337 1.58 0.879 2.121s1.293 0.879 2.121 0.879h14c0.828 0 1.58-0.337 2.121-0.879s0.879-1.293 0.879-2.121v-7c0-0.552-0.448-1-1-1s-1 0.448-1 1v7c0 0.276-0.111 0.525-0.293 0.707s-0.431 0.293-0.707 0.293h-14c-0.276 0-0.525-0.111-0.707-0.293s-0.293-0.431-0.293-0.707v-14c0-0.276 0.111-0.525 0.293-0.707s0.431-0.293 0.707-0.293h7c0.552 0 1-0.448 1-1s-0.448-1-1-1zM17.793 1.793l-9.5 9.5c-0.122 0.121-0.217 0.28-0.263 0.465l-1 4c-0.039 0.15-0.042 0.318 0 0.485 0.134 0.536 0.677 0.862 1.213 0.728l4-1c0.167-0.041 0.33-0.129 0.465-0.263l9.5-9.5c0.609-0.609 0.914-1.41 0.914-2.207s-0.305-1.598-0.914-2.207-1.411-0.915-2.208-0.915-1.598 0.305-2.207 0.914zM19.207 3.207c0.219-0.219 0.504-0.328 0.793-0.328s0.574 0.109 0.793 0.328 0.328 0.504 0.328 0.793-0.109 0.574-0.328 0.793l-9.304 9.304-2.114 0.529 0.529-2.114z"
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
                  viewBox="0 0 26 26"
                >
                  <path
                    d="M21 21v-2c0-1.38-0.561-2.632-1.464-3.536s-2.156-1.464-3.536-1.464h-8c-1.38 0-2.632 0.561-3.536 1.464s-1.464 2.156-1.464 3.536v2c0 0.552 0.448 1 1 1s1-0.448 1-1v-2c0-0.829 0.335-1.577 0.879-2.121s1.292-0.879 2.121-0.879h8c0.829 0 1.577 0.335 2.121 0.879s0.879 1.292 0.879 2.121v2c0 0.552 0.448 1 1 1s1-0.448 1-1zM17 7c0-1.38-0.561-2.632-1.464-3.536s-2.156-1.464-3.536-1.464-2.632 0.561-3.536 1.464-1.464 2.156-1.464 3.536 0.561 2.632 1.464 3.536 2.156 1.464 3.536 1.464 2.632-0.561 3.536-1.464 1.464-2.156 1.464-3.536zM15 7c0 0.829-0.335 1.577-0.879 2.121s-1.292 0.879-2.121 0.879-1.577-0.335-2.121-0.879-0.879-1.292-0.879-2.121 0.335-1.577 0.879-2.121 1.292-0.879 2.121-0.879 1.577 0.335 2.121 0.879 0.879 1.292 0.879 2.121z"
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
                  viewBox="0 0 28 28"
                >
                  <path
                    d="M21 11.080v0.92c-0.001 2.485-1.009 4.733-2.64 6.362s-3.88 2.634-6.365 2.632-4.734-1.009-6.362-2.64-2.634-3.879-2.633-6.365 1.009-4.733 2.64-6.362 3.88-2.634 6.365-2.633c1.33 0.001 2.586 0.289 3.649 0.775 0.502 0.23 1.096 0.008 1.325-0.494s0.008-1.096-0.494-1.325c-1.327-0.606-2.866-0.955-4.479-0.956-3.037-0.002-5.789 1.229-7.78 3.217s-3.224 4.74-3.226 7.777 1.229 5.789 3.217 7.78 4.739 3.225 7.776 3.226 5.789-1.229 7.78-3.217 3.225-4.739 3.227-7.777v-0.92c0-0.552-0.448-1-1-1s-1 0.448-1 1zM21.293 3.293l-9.293 9.302-2.293-2.292c-0.391-0.391-1.024-0.391-1.414 0s-0.391 1.024 0 1.414l3 3c0.391 0.391 1.024 0.39 1.415 0l10-10.010c0.39-0.391 0.39-1.024-0.001-1.414s-1.024-0.39-1.414 0.001z"
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
      <main class="flex flex-1 bg-gray-200">
        <!-- Inbox Preview Emails -->
        <div
          class="relative flex flex-col w-full max-w-xs flex-grow border-l border-r bg-gray-200"
        >
          <!-- Sort Date row -->
          <div
            class="flex-shrink-0 px-4 py-2 flex items-center justify-between border-b"
          >
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
                class="pt-1 h-6 w-6 fill-current text-gray-500"
                viewBox="0 0 40 40"
              >
                <path d="M10 24v-24h-4v24h-5l7 7 7-7h-5z"></path>
                <path d="M14 18h18v4h-18v-4z"></path>
                <path d="M14 12h14v4h-14v-4z"></path>
                <path d="M14 6h10v4h-10v-4z"></path>
                <path d="M14 0h6v4h-6v-4z"></path>
              </svg>
            </button>
          </div>
          <!-- Email preview block -->
          <div class="flex-1 overflow-y-auto">
            <div class="border-l-4 border-indigo-500">
              <a href="#" class="block px-6 pt-3 pb-4 border-b bg-gray-100">
                <div class="flex justify-between">
                  <span class="text-sm font-semibold text-gray-900"
                    >Jonathan Maberry</span
                  >
                  <span class="text-sm text-gray-600">2 days ago</span>
                </div>
                <p class="text-sm text-gray-900">
                  Author Discount?
                </p>
                <p class="mt-2 text-sm text-gray-600">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer
                  gravida tristique lectus. Nullam in lacus dui...
                </p>
              </a>
            </div>
            <div class="">
              <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b hover:bg-indigo-100">
                <div class="flex justify-between">
                  <span class="text-sm font-semibold text-gray-900"
                    >Dan Brown</span
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
            <div>
              <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b hover:bg-indigo-100">
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
            <div class="border-l-4 border-indigo-500">
              <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b hover:bg-indigo-100">
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
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b hover:bg-indigo-100">
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
            <a href="#" class="block px-6 pt-3 pb-4 bg-white border-b hover:bg-indigo-100">
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
        <div class="flex-1 flex flex-col w-0">
          <div class="relative shadow-md">
            <!-- Email Thread Action Icons -->
            <div class="px-5 py-4 flex items-center bg-gray-100 border-b">
              <button>
                <svg
                  class="h-6 w-6 fill-current text-gray-600"
                  viewBox="0 0 40 40"
                >
                  <path
                    d="M16 32c8.837 0 16-7.163 16-16s-7.163-16-16-16-16 7.163-16 16 7.163 16 16 16zM16 3c7.18 0 13 5.82 13 13s-5.82 13-13 13-13-5.82-13-13 5.82-13 13-13z"
                  ></path>
                  <path
                    d="M20.914 9.914l-2.829-2.829-8.914 8.914 8.914 8.914 2.828-2.828-6.086-6.086z"
                  ></path>
                </svg>
              </button>
              <button class="ml-6">
                <svg
                  class="pt-0 h-6 w-6 fill-current text-gray-600"
                  viewBox="0 0 28 28"
                >
                  <path
                    d="M21.297 14.117c0.583-0.586 0.874-1.352 0.874-2.115 0.001-0.764-0.29-1.532-0.874-2.12l-8.59-8.59c-0.181-0.18-0.431-0.292-0.707-0.292h-10c-0.552 0-1 0.448-1 1v10c0 0.256 0.098 0.512 0.293 0.708l8.592 8.582c0.586 0.585 1.356 0.878 2.122 0.877s1.536-0.294 2.12-0.879zM19.883 12.703l-7.17 7.17c-0.196 0.196-0.45 0.294-0.707 0.294s-0.512-0.097-0.707-0.292l-8.299-8.29v-8.585h8.586l8.297 8.297c0.192 0.193 0.289 0.447 0.289 0.704s-0.097 0.509-0.289 0.702zM7 8c0.552 0 1-0.448 1-1s-0.448-1-1-1-1 0.448-1 1 0.448 1 1 1z"
                  ></path>
                </svg>
              </button>
              <button class="ml-6">
                <svg
                  class="h-6 w-6 fill-current text-gray-600"
                  viewBox="0 0 28 28"
                >
                  <path
                    d="M21 21v-2c0-1.38-0.561-2.632-1.464-3.536s-2.156-1.464-3.536-1.464h-8c-1.38 0-2.632 0.561-3.536 1.464s-1.464 2.156-1.464 3.536v2c0 0.552 0.448 1 1 1s1-0.448 1-1v-2c0-0.829 0.335-1.577 0.879-2.121s1.292-0.879 2.121-0.879h8c0.829 0 1.577 0.335 2.121 0.879s0.879 1.292 0.879 2.121v2c0 0.552 0.448 1 1 1s1-0.448 1-1zM17 7c0-1.38-0.561-2.632-1.464-3.536s-2.156-1.464-3.536-1.464-2.632 0.561-3.536 1.464-1.464 2.156-1.464 3.536 0.561 2.632 1.464 3.536 2.156 1.464 3.536 1.464 2.632-0.561 3.536-1.464 1.464-2.156 1.464-3.536zM15 7c0 0.829-0.335 1.577-0.879 2.121s-1.292 0.879-2.121 0.879-1.577-0.335-2.121-0.879-0.879-1.292-0.879-2.121 0.335-1.577 0.879-2.121 1.292-0.879 2.121-0.879 1.577 0.335 2.121 0.879 0.879 1.292 0.879 2.121z"
                  ></path>
                </svg>
              </button>
              <button class="ml-6">
                <svg
                  class="h-6 w-6 fill-current text-gray-600"
                  viewBox="0 0 28 28"
                >
                  <path
                    d="M20 15v4c0 0.276-0.111 0.525-0.293 0.707s-0.431 0.293-0.707 0.293h-14c-0.276 0-0.525-0.111-0.707-0.293s-0.293-0.431-0.293-0.707v-4c0-0.552-0.448-1-1-1s-1 0.448-1 1v4c0 0.828 0.337 1.58 0.879 2.121s1.293 0.879 2.121 0.879h14c0.828 0 1.58-0.337 2.121-0.879s0.879-1.293 0.879-2.121v-4c0-0.552-0.448-1-1-1s-1 0.448-1 1zM13 12.586v-9.586c0-0.552-0.448-1-1-1s-1 0.448-1 1v9.586l-3.293-3.293c-0.391-0.391-1.024-0.391-1.414 0s-0.391 1.024 0 1.414l5 5c0.092 0.092 0.202 0.166 0.324 0.217s0.253 0.076 0.383 0.076c0.256 0 0.512-0.098 0.707-0.293l5-5c0.391-0.391 0.391-1.024 0-1.414s-1.024-0.391-1.414 0z"
                  ></path>
                </svg>
              </button>
              <button class="ml-6">
                <svg
                  class="h-6 w-6 fill-current text-gray-600"
                  viewBox="0 0 28 28"
                >
                  <path
                    d="M10.001 7.8c-1.215 0-2.201 0.985-2.201 2.2s0.986 2.2 2.201 2.2c1.215 0 2.199-0.985 2.199-2.2s-0.984-2.2-2.199-2.2zM3.001 7.8c-1.215 0-2.201 0.985-2.201 2.2s0.986 2.2 2.201 2.2c1.215 0 2.199-0.986 2.199-2.2s-0.984-2.2-2.199-2.2zM17.001 7.8c-1.215 0-2.201 0.985-2.201 2.2s0.986 2.2 2.201 2.2c1.215 0 2.199-0.985 2.199-2.2s-0.984-2.2-2.199-2.2z"
                  ></path>
                </svg>
              </button>
              <button class="ml-auto ">
                <svg
                  class="h-4 w-4 stroke-current text-gray-600"
                  fill="currentColor"
                  viewBox="0 0 22 22"
                >
                  <path
                    d="M5.293 9.707l6 6c0.391 0.391 1.024 0.391 1.414 0l6-6c0.391-0.391 0.391-1.024 0-1.414s-1.024-0.391-1.414 0l-5.293 5.293-5.293-5.293c-0.391-0.391-1.024-0.391-1.414 0s-0.391 1.024 0 1.414z"
                  ></path>
                </svg>
              </button>
              <button class="ml-4">
                <svg
                  class="h-4 w-4 stroke-current text-gray-600"
                  fill="currentColor"
                  viewBox="0 0 22 22"
                >
                  <path
                    d="M18.707 14.293l-6-6c-0.391-0.391-1.024-0.391-1.414 0l-6 6c-0.391 0.391-0.391 1.024 0 1.414s1.024 0.391 1.414 0l5.293-5.293 5.293 5.293c0.391 0.391 1.024 0.391 1.414 0s0.391-1.024 0-1.414z"
                  ></path>
                </svg>
              </button>
            </div>
            <!-- Email Title Section -->
            <div class="flex items-center justify-between bg-white px-5 p-4">
              <h3 class="text-xl text-gray-900 truncate">
                Re: Author Discount?
              </h3>
              <div class="flex-shrink-0 ml-4">
                <span class="">#3822</span>
                <span
                  class="text-xs ml-3 font-semibold text-green-900 bg-green-200 rounded-full leading-none px-2 py-1"
                >
                  Action
                </span>
              </div>
            </div>
          </div>
          <div class="p-3 flex-1 overflow-y-auto">
            <article class="px-10 pt-6 pb-8 bg-white rounded-lg shadow">
              <div class="flex items-center justify-between">
                <p class="text-lg font-medium">
                  <span class="text-gray-900">Jonathan Maberry</span>
                  <span class="ml-1 text-gray-600">wrote</span>
                </p>
                <div class="flex items-center">
                  <span class="text-sm text-gray-600">
                    Yesterday at 8:20am
                  </span>
                  <img
                    class="ml-5 h-8 w-8 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1480455624313-e29b44bbfde1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=5&w=144&h=144&q=80"
                    alt=""
                  />
                </div>
              </div>
              <div class="mt-6 text-gray-800 text-sm">
                <p>
                  Thanks so much!! Can't wait to try it out :)
                </p>
              </div>
            </article>
            <article class="px-10 py-6 mt-3 bg-white rounded-lg shadow">
              <div class="flex items-center justify-between">
                <p class="text-lg font-medium">
                  <span class="text-gray-900">Monica White</span>
                  <span class="ml-1 text-gray-600">replied</span>
                </p>
                <div class="flex items-center">
                  <span class="text-sm text-gray-600">
                    July 10th, 2020 at 12:21pm
                  </span>
                  <img
                    class="ml-5 h-8 w-8 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=3&w=144&h=144&q=80"
                    alt=""
                  />
                </div>
              </div>
              <div class="mt-6 text-gray-800 text-sm">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Integer gravida tristique lectus. Nullam in lacus dui.
                </p>
                <p class="mt-4">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Integer gravida tristique lectus. Nullam in lacus dui. Sed et
                  lorem luctus, euismod velit ac, bibendum enim. Etiam varius
                  odio et vestibulum pretium. Nam a nisl egestas, porta augue
                  nec, ultricies ipsum. Nulla facilisi. Etiam hendrerit aliquet
                  varius. Integer sit amet ultrices dui.
                </p>
                <p class="mt-6 font-semibold text-gray-900">Monica White</p>
                <p class="text-gray-800">Customer Service</p>
              </div>
            </article>
            <article class="px-10 py-6 mt-3 bg-white rounded-lg shadow">
              <div class="flex items-center justify-between">
                <p class="text-lg font-medium">
                  <span class="text-gray-900">Jonathan Maberry</span>
                  <span class="ml-1 text-gray-600">wrote</span>
                </p>
                <div class="flex items-center">
                  <span class="text-sm text-gray-600">
                    July 2nd, 2020 at 19:21pm
                  </span>
                  <img
                    class="ml-5 h-8 w-8 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1480455624313-e29b44bbfde1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=5&w=144&h=144&q=80"
                    alt=""
                  />
                </div>
              </div>
              <div class="mt-6 text-gray-800 text-sm">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Integer gravida tristique lectus. Nullam in lacus dui. Sed et
                  lorem luctus, euismod velit ac, bibendum enim. Etiam varius
                  odio et vestibulum pretium. Nam a nisl egestas, porta augue
                  nec, ultricies ipsum. Nulla facilisi. Etiam hendrerit aliquet
                  varius. Integer sit amet ultrices dui. Maecenas adipiscing
                  mauris magna, eget iaculis odio faucibus quis. Nulla facilisi.
                  Ut dapibus hendrerit ultricies. Cras facilisis congue
                  consequat. Fusce ultrices ut dolor sit amet vehicula. Donec
                  euismod augue leo. Nunc semper nisi eu velit consectetur, a
                  lacinia erat aliquet.
                </p>
              </div>
            </article>
            <article class="px-10 py-6 mt-3 bg-white rounded-lg shadow">
              <div class="flex items-center justify-between">
                <p class="text-lg font-medium">
                  <span class="text-gray-900">Jonathan Maberry</span>
                  <span class="ml-1 text-gray-600">wrote</span>
                </p>
                <div class="flex items-center">
                  <span class="text-sm text-gray-600">
                    July 2nd, 2020 at 9:21am
                  </span>
                  <img
                    class="ml-5 h-8 w-8 rounded-full object-cover"
                    src="https://images.unsplash.com/photo-1480455624313-e29b44bbfde1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=5&w=144&h=144&q=80"
                    alt=""
                  />
                </div>
              </div>
              <div class="mt-6 text-gray-800 text-sm">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Integer gravida tristique lectus. Nullam in lacus dui. Sed et
                  lorem luctus, euismod velit ac, bibendum enim. Etiam varius
                  odio et vestibulum pretium. Nam a nisl egestas, porta augue
                  nec, ultricies ipsum. Nulla facilisi. Etiam hendrerit aliquet
                  varius. Integer sit amet ultrices dui. Maecenas adipiscing
                  mauris magna, eget iaculis odio faucibus quis. Nulla facilisi.
                  Ut dapibus hendrerit ultricies. Cras facilisis congue
                  consequat. Fusce ultrices ut dolor sit amet vehicula. Donec
                  euismod augue leo. Nunc semper nisi eu velit consectetur, a
                  lacinia erat aliquet.
                </p>
              </div>
            </article>
          </div>
        </div>
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
