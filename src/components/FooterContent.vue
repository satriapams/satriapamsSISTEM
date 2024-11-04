<template>
    <footer class="bg-gray-900 text-white py-8 px-6 md:px-10">
      <div class="container mx-auto px-4">
        <!-- Logo and Navigation -->
        <div class="flex justify-between items-center mb-6">
          <!-- Logo -->
          <div class="text-2xl font-bold">{ Finsweet }</div>
  
          <!-- Navigation Links -->
          <div class="flex space-x-4">
            <router-link to="/" class="hover:underline">Home</router-link>
            <router-link to="/blog" class="hover:underline">Blog</router-link>
            <router-link to="/aboutus" class="hover:underline">About us</router-link>
            <router-link to="/contact" class="hover:underline">Contact us</router-link>
            <router-link to="/privacy" class="hover:underline">Privacy Policy</router-link>
          </div>
        </div>
  
        <!-- Subscribe Section with Border -->
        <div
          class="bg-gray-700 rounded-lg p-6 mb-6 flex flex-col md:flex-row justify-between items-center space-y-4 md:space-y-0"
        >
          <div class="text-xl text-center md:text-left">
            Subscribe to our newsletter to get latest updates and news
          </div>
          <div class="flex items-center space-x-4">
            <input
              type="email"
              placeholder="Enter Your Email"
              class="px-20 py-2 pl-2 rounded bg-gray-800 border border-gray-700 text-white focus:outline-none"
            />
            <button
              class="px-6 py-2 bg-blue-600 hover:bg-blue-500 rounded text-white"
            >
              Subscribe
            </button>
          </div>
        </div>
  
        <!-- Contact Info and Social Icons -->
        <div
          class="flex flex-col md:flex-row justify-between items-center text-sm space-y-4 md:space-y-0"
        >
          <div class="text-center md:text-left">
            Finstreet 118 2561 Fintown <br />
            <router-link to="mailto:Hello@finsweet.com" class="hover:underline"
              >Hello@finsweet.com</router-link
            >
            <br />
            020 7993 2905
          </div>
          <div class="flex space-x-4">
            <!-- Social Media Icons here -->
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <style scoped>
  /* Menambahkan padding di elemen footer */
  footer {
    padding-left: 2rem;
    padding-right: 2rem;
  }
  </style>
  