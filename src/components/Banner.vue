<template>
    <header class="bg-gray-700 h-screen text-white">
      <div class="container mx-auto">
        <nav class="p-4 lg:p-0 lg:py-6">
          <div class="flex items-center justify-between">
            <a href="#" class="flex items-center space-x-2">
              <img class="w-12 h-12 lg:w-20 lg:h-20 rounded-full" src="https://s3.amazonaws.com/uifaces/faces/twitter/derekcramer/128.jpg" alt="avatar"/>
              <span class="font-semibold text-2xl">shoppefly</span>
            </a>
  
            <div class="lg:hidden">
              <svg v-if="!isOpen" @click="isOpen = !isOpen" class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
              <svg v-if="isOpen" @click="isOpen = !isOpen" class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            </div>
  
            <div class="hidden lg:flex items-center space-x-12">
              <ul class="flex items-center space-x-4">
                <li><a href="#">Requesting</a></li>
                <li><a href="#">Traveling</a></li>
                <li><a href="#">How it works</a></li>
              </ul>
              <input class="bg-white w-64 px-4 py-3 rounded-md placeholder-gray-600 focus:outline-none" type="text" placeholder="Search for users or items">
              <button class="px-8 py-3 font-bold rounded-md uppercase focus:outline-none bg-green-500 hover:bg-green-600">Login</button>
            </div>
          </div>
  
          <div v-show="isOpen" class="lg:hidden">
            <div class="border border-t border-gray-600 mt-6"></div>
            <ul class="flex flex-col space-y-2 mt-6">
                <li><a class="hover:text-gray-500" href="#">Requesting</a></li>
                <li><a class="hover:text-gray-500" href="#">Traveling</a></li>
                <li><a class="hover:text-gray-500" href="#">How it works</a></li>
                <li><input class="text-xs px-4 py-2 bg-white w-full lg:w-64 rounded placeholder-gray-600 focus:outline-none" type="text" placeholder="Search for users or items"></li>
                <li><button class="text-xs px-4 py-2 font-bold rounded uppercase focus:outline-none bg-green-500 hover:bg-green-600 w-full">Login</button></li>
            </ul>
          </div>
        </nav>

        <div class="text-center space-y-6 lg:space-y-12 mt-20">
          <h1 class="text-2xl lg:text-6xl font-semibold text-center">We Belive. We Say. We Delivery</h1>
          <p class="text-base lg:text-2xl text-center">Let the travelers deliver you anything you desire from everywhere around the globe.</p>
          <div class="flex items-center justify-center font-semibold text-xs lg:text-base space-x-4 lg:space-x-24">
            <button class="bg-green-500 focus:outline-none hover:bg-green-600  w-40 lg:w-64 px-6 py-4 lg:px-16 lg:py-6 uppercase rounded-md">Sign Up</button>
            <button class="border border-white focus:outline-none hover:bg-gray-600 w-40 px-6 lg:w-64 py-4 lg:px-16 lg:py-6 uppercase rounded-md">Virtual Tour</button>
          </div>
        </div>
      </div>
    </header>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false
    }
  }
}
</script>

<style>

</style>