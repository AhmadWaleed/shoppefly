<template>
  <div id="app">
    
    <banner></banner>

    <main class="container mx-auto my-16">
      <section class="how-it-works space-y-12 bg-white">
        <section class="requester space-y-12">
          <h2 class="font-bold text-3xl text-center">Are you a requester? how it works:</h2>
          <div class="flex items-center">
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/business" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/fashion" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/transport" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/city" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
          </div>
          <div class="flex justify-center font-semibold space-x-8">
            <button class="bg-green-500 text-white focus:outline-none hover:bg-green-600 px-4 w-48 py-4 uppercase rounded-md">Post a Request</button>
            <button class="border text-green-500 border-green-500 focus:outline-none  hover:bg-green-500 w-48 hover:text-white  px-4 py-4 uppercase rounded-md">Watch Video</button>
          </div>
        </section>
        <section class="traveler space-y-12">
          <h2 class="font-bold text-3xl text-center">Are you a Traveler? how it works:</h2>
          <div class="flex items-center">
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/cats" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/people" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/nature" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
            <div class="flex flex-col items-center space-y-8 space-x-2 text-center">
              <img class="w-40 h-40 rounded-full border-4 border-gray-700" src="http://lorempixel.com/640/480/animals" alt="image ">
              <p class="text-xs text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, laboriosam.</p>  
            </div>
          </div>
          <div class="flex justify-center font-semibold space-x-8">
            <button class="bg-green-500 text-white focus:outline-none hover:bg-green-600 px-4 w-48 py-4 uppercase rounded-md">Post a Trip</button>
            <button class="border text-green-500 border-green-500 focus:outline-none  hover:bg-green-500 w-48 hover:text-white  px-4 py-4 uppercase rounded-md">Watch Video</button>
          </div>
        </section>
        <section class="be-a-requester space-y-12">
          <h2 class="font-bold text-3xl text-center">Be a Requester and...</h2>
          <div class="flex space-x-24 justify-center">
            <div class="flex border border-gray-900 rounded-md p-4 w-1/5">
              <div class="flex flex-col space-y-6 items-center text-center">
                <img class="border-4 border-gray-700 w-24 h-24 rounded-full" src="http://lorempixel.com/640/480/nature" alt="image">
                <p class="text-xs">Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, veniam!</p>
              </div>
            </div>
            <div class="flex border border-gray-900 rounded-md p-4 w-1/5">
              <div class="flex flex-col space-y-6 items-center text-center">
                <img class="border-4 border-gray-700 w-24 h-24 rounded-full" src="http://lorempixel.com/640/480/transport" alt="image">
                <p class="text-xs">Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, veniam!</p>
              </div>
            </div>
            <div class="flex border border-gray-900 rounded-md p-4 w-1/5">
              <div class="flex flex-col space-y-6 items-center text-center">
                <img class="border-4 border-gray-700 w-24 h-24 rounded-full" src="http://lorempixel.com/640/480/abstract" alt="image">
                <p class="text-xs">Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, veniam!</p>
              </div>
            </div>
          </div>
        </section>
        <section class="be-a-traveler space-y-12">
          <h2 class="font-bold text-3xl text-center">Be a Traveler and...</h2>
          <div class="flex space-x-24 justify-center">
            <div class="flex border border-gray-900 rounded-md p-4 w-1/5">
              <div class="flex flex-col space-y-6 items-center text-center">
                <img class="border-4 border-gray-700 w-24 h-24 rounded-full" src="http://lorempixel.com/640/480/nature" alt="image">
                <p class="text-xs">Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, veniam!</p>
              </div>
            </div>
            <div class="flex border border-gray-900 rounded-md p-4 w-1/5">
              <div class="flex flex-col space-y-6 items-center text-center">
                <img class="border-4 border-gray-700 w-24 h-24 rounded-full" src="http://lorempixel.com/640/480/fashion" alt="image">
                <p class="text-xs">Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, veniam!</p>
              </div>
            </div>
            <div class="flex border border-gray-900 rounded-md p-4 w-1/5">
              <div class="flex flex-col space-y-6 items-center text-center">
                <img class="border-4 border-gray-700 w-24 h-24 rounded-full" src="http://lorempixel.com/640/480/business" alt="image">
                <p class="text-xs">Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, veniam!</p>
              </div>
            </div>
          </div>
        </section>
      </section>
    </main>

    <section class="recent-posts p-6 bg-gray-300 mt-8 flex text-center">
        <div class="w-3/6 space-y-12">
          <h2 class="text-2xl font-semibold">Recently Posted Requests</h2>
          <div class="flex flex-col items-center space-y-8">
            <div class="p-4 w-4/5 bg-white border-l-8 border-yellow-600 rounded-md shadow-lg">
            <div class="flex justify-between">
              <a class="flex items-center space-x-2" href="#">
                <img class="rounded-full w-12 h-12" src="https://s3.amazonaws.com/uifaces/faces/twitter/arpitnj/128.jpg" alt="avatar">
                <span class="text-green-500 font-semibold">username</span>
              </a>
              <ul class="flex item-center space-x-2">
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/lhausermann/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/axel/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/mbilderbach/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/vivekprvr/128.jpg" alt="avatar"></li>
              </ul>
            </div>
            <div class="flex">
              <div class="w-1/5 mt-4">
                <ul class="flex flex-col space-y-2 text-gray-600 text-xs">
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/city" alt="image"><span>0 offers sent</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/transport" alt="image"><span>3 items</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/abstract" alt="image"><span>RS 10,000</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/nightlife" alt="image"><span>5.0</span></li>
                </ul>
            </div>
            <div class="w-4/5 flex flex-col mt-4">
              <div class="flex items-center justify-center space-x-2 text-gray-800 font-semibold">
                <div>Washington, USA</div>
                <img class="w-8 h-8" src="http://lorempixel.com/640/480/nature" alt="image">
                <div>Lahore, Pakistan</div>
              </div>
              <div class="flex justify-end space-x-12 mt-10">
                <h2 class="text-4xl text-green-500 font-semibold">Rs. 2,500</h2>
                <button class="px-3 py-3 bg-green-500 hover:bg-green-600 focus:outline-none text-white rounded-md mr-0">Send an offer</button>
              </div>
            </div>
            </div>
          </div>
          <div class="p-4 w-4/5 bg-white border-l-8 border-yellow-600 rounded-md shadow-lg">
            <div class="flex justify-between">
              <a class="flex items-center space-x-2" href="#">
                <img class="rounded-full w-12 h-12" src="https://s3.amazonaws.com/uifaces/faces/twitter/mikaeljorhult/128.jpg" alt="avatar">
                <span class="text-green-500 font-semibold">username</span>
              </a>
              <ul class="flex item-center space-x-2">
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/lhausermann/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/axel/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/mbilderbach/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/vivekprvr/128.jpg" alt="avatar"></li>
              </ul>
            </div>
            <div class="flex">
              <div class="w-1/5 mt-4">
                <ul class="flex flex-col space-y-2 text-gray-600 text-xs">
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/transport" alt="image"><span>0 offers sent</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/sports" alt="image"><span>3 items</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/abstract" alt="image"><span>RS 10,000</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/cats" alt="image"><span>5.0</span></li>
                </ul>
            </div>
            <div class="w-4/5 flex flex-col mt-4">
              <div class="flex items-center justify-center space-x-2 text-gray-800 font-semibold">
                <div>Washington, USA</div>
                <img class="w-8 h-8" src="http://lorempixel.com/640/480/animals" alt="image">
                <div>Lahore, Pakistan</div>
              </div>
              <div class="flex justify-end space-x-12 mt-10">
                <h2 class="text-4xl text-green-500 font-semibold">Rs. 2,500</h2>
                <button class="px-3 py-3 bg-green-500 hover:bg-green-600 focus:outline-none text-white rounded-md mr-0">Send an offer</button>
              </div>
            </div>
            </div>
          </div>
          </div>
          <button class="w-48 px-6 py-4 bg-green-500 hover:bg-green-600 rounded-md focus:outline-none text-white">View All Requests</button>
        </div>
        <div class="w-3/6 space-y-12">
          <h2 class="text-2xl font-semibold">Recently Posted Trips</h2>
          <div class="flex flex-col items-center space-y-8">
            <div class="p-4 w-4/5 rounded-md shadow-lg bg-local text-white" style="background-image: url('https://images.unsplash.com/photo-1485738422979-f5c462d49f74?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80')">
            <div class="flex justify-between">
              <a class="flex items-center space-x-2" href="#">
                <img class="rounded-full w-12 h-12" src="https://s3.amazonaws.com/uifaces/faces/twitter/chatyrko/128.jpg" alt="avatar">
                <span class="font-semibold">username</span>
              </a>
              <ul class="flex item-center space-x-2">
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/lhausermann/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/axel/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/mbilderbach/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/mbilderbach/128.jpg" alt="avatar"></li>
              </ul>
            </div>
            <div class="flex">
              <div class="w-1/5 mt-4">
                <ul class="flex flex-col space-y-6 text-xs">
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/animals" alt="image"><span>10th Jul, 2020</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/abstract" alt="image"><span>Max Rs. 5,00</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/food" alt="image"><span>Not rated yet</span></li>
                </ul>
            </div>
            <div class="w-4/5 flex flex-col mt-4">
              <div class="flex items-center justify-center space-x-2 font-semibold">
                <div>Washington, USA</div>
                <img class="w-8 h-8" src="http://lorempixel.com/640/480/transport" alt="image">
                <div>Lahore, Pakistan</div>
              </div>
              <div class="flex justify-end space-x-12 mt-10">
                <button class="px-3 py-3 bg-white text-green-500 focus:outline-none hover:bg-gray-100 rounded-md mr-0">Send a request</button>
              </div>
            </div>
            </div>
          </div>
          <div class="p-4 w-4/5 rounded-md shadow-lg bg-local text-white" style="background-image: url('https://images.unsplash.com/photo-1485738422979-f5c462d49f74?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80')">
            <div class="flex justify-between">
              <a class="flex items-center space-x-2" href="#">
                <img class="rounded-full w-12 h-12" src="https://s3.amazonaws.com/uifaces/faces/twitter/eyronn/128.jpg" alt="avatar">
                <span class="font-semibold">username</span>
              </a>
              <ul class="flex item-center space-x-2">
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/lhausermann/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/axel/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/mbilderbach/128.jpg" alt="avatar"></li>
                <li><a href="#"></a><img class="rounded-full w-5 h-5" src="https://s3.amazonaws.com/uifaces/faces/twitter/mbilderbach/128.jpg" alt="avatar"></li>
              </ul>
            </div>
            <div class="flex">
              <div class="w-1/5 mt-4">
                <ul class="flex flex-col space-y-6 text-xs">
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/animals" alt="image"><span>10th Jul, 2020</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/cats" alt="image"><span>Max Rs. 5,00</span></li>
                  <li class="flex items-center space-x-2 space-y-2"><img class="w-4 h-4" src="http://lorempixel.com/640/480/business" alt="image"><span>Not rated yet</span></li>
                </ul>
            </div>
            <div class="w-4/5 flex flex-col mt-4">
              <div class="flex items-center justify-center space-x-2 font-semibold">
                <div>Washington, USA</div>
                <img class="w-8 h-8" src="http://lorempixel.com/640/480/people" alt="image">
                <div>Lahore, Pakistan</div>
              </div>
              <div class="flex justify-end space-x-12 mt-10">
                <button class="px-3 py-3 bg-white text-green-500 focus:outline-none hover:bg-gray-100 rounded-md mr-0">Send a request</button>
              </div>
            </div>
            </div>
          </div>
          </div>
          <button class="w-48 px-6 py-4 bg-green-500 hover:bg-green-600 rounded-md focus:outline-none text-white">View All Trip</button>
        </div>
      </section>
  </div>
</template>

<script>
import Banner from './components/Banner';
export default {
  name: "App",
  components: {
    Banner
  },
};
</script>
