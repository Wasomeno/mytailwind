<template>
<div class="sea container min-w-full min-h-full">
  <div id="navbar-left" class="absolute z-10 m-2 w-1/2 bg-transparent">
      <ul class="flex justify-around items-center">
        <li><img src="../assets/logo.png" class="w-8 sm:w-16" alt=""></li>
        <li class="text-white text-xs mr-2 sm:text-base "><a href="#">Home</a></li>
        <li class="text-white text-xs mr-2 sm:text-base "><a href="#">About</a></li>
        <li class="text-white text-xs mr-2 sm:text-base "><a href="#">Contact Us</a></li>
      </ul>
  </div>
  <div id="navbar-right" class="right-0 absolute z-10 m-5 sm:m-7 w-1/2 bg-transparent">
      <ul class="flex justify-end items-center">
        <li class="text-white text-xs sm:text-base mx-2">Login</li>
        <li class="text-white text-xs sm:text-base mx-2">Sign Up</li>
      </ul>
  </div>
  <div class="top-section h-screen flex">
    <transition appear @enter="anim1" :css="false">
    <div class="left-side bg-cyprus flex items-center  w-1/2 sm:w-1/2 bg-blue-300" id="left-side">
      <div class="left-content text-center text-white">
        <div class="flex-none text-content p-5">
          <h2 class="text-xl sm:text-2xl font-semibold">What Is Sea ?</h2>
            <p class="text-xs sm:text-base p-5 font-thin">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore et dolore
              magna aliqua. Ut enim ad minim veniam, quis nostrud
              exercitation ullamco laboris nisi ut aliquip ex ea commodo
              consequat. Duis aute irure dolor in reprehenderit in voluptate
              velit esse cillum dolore eu fugiat nulla pariatur.</p>
              <button class="btn-primary bg-deepsea hover:bg-breaker text-xs sm:text-sm p-2 rounded-full w-24 sm:w-32">Learn More</button>
          </div>
        </div>
    </div>
    </transition>
  <transition appear @enter="anim1" :css="false">
  <div class="h-screen w-1/2 h-1/2 bg-cover bg-center" id="right-side">
  </div>
  </transition>
  </div>

 <div class="mid-section my-5 h-screen">
      <div class="content">
          <h2 class="text-xl sm:text-2xl text-center font-semibold p-5 my-3">Sea Creatures ?</h2>
          <div class="cards-container flex justify-around">
            <div class="max-w-xs rounded overflow-hidden shadow-lg text-center mx-2">
              <img class="w-full h-56" src="../assets/turtle1.gif">
              <div class="px-6 py-4">
              <div class="font-bold text-base sm:text-xl mb-2">Turtles</div>
              <p class="text-gray-600 text-xs sm:text-base">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore et dolore
              magna aliqua. Ut enim ad minim veniam, quis nostrud
              exercitation ullamco laboris nisi ut aliquip ex ea commodo</p>
            </div>
            <button class="btn-primary bg-white hover:bg-botticelli text-sm p-2 m-5 rounded-full w-24 sm:w-32">Learn More</button>
            </div>
            <div class="max-w-xs rounded overflow-hidden shadow-lg text-center mx-2">
              <img class="w-full h-56" src="../assets/reef.gif">
              <div class="px-6 py-4">
              <div class="font-bold text-sm sm:text-xl mb-2">Fishes</div>
              <p class="text-gray-600 text-xs sm:text-base">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore et dolore
              magna aliqua. Ut enim ad minim veniam, quis nostrud
              exercitation ullamco laboris nisi ut aliquip ex ea commodo</p>
            </div>
            <button class="btn-primary bg-white hover:bg-botticelli text-sm p-2 m-5 rounded-full w-24 sm:w-32">Learn More</button>
            </div>
            <div class="max-w-xs rounded overflow-hidden shadow-lg text-center mx-2">
              <img class="w-full h-56" src="../assets/dolphins.gif">
              <div class="px-6 py-4">
              <div class="font-bold text-base sm:text-xl mb-2">Dolphins</div>
              <p class="text-gray-600 text-xs sm:text-base  ">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore et dolore
              magna aliqua. Ut enim ad minim veniam, quis nostrud
              exercitation ullamco laboris nisi ut aliquip ex ea commodo</p>
            </div>
            <button class="btn-primary bg-white hover:bg-botticelli text-sm p-2 m-5 rounded-full w-24 sm:w-32">Learn More</button>
            </div>
          </div>
      </div>
  </div>
  <div class="bottom-section h-screen flex">
  <div class="h-screen w-1/2 h-1/2 bg-cover bg-center" id="left-bottom">
  </div>
  <div class="bg-white w-1/2 bg-blue-300" id="right-bottom">
      <div class="right-content">
        <div class="text-content p-5 m-5">
          <h2 class="text-lg sm:text-2xl text-center font-semibold">Want to learn more about Sea ?</h2>
          <h6 class="text-xs sm:text-sm text-center">Fill the form below and submit it to us !</h6>
        </div>
  <form class="flex flex-col items-center justify-center">
  <div class=" sm:flex flex-wrap justify-center -mx-3 mb-6">
    <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
        First Name
      </label>
      <input class="appearance-none block w-48 sm:w-full bg-gray-200 text-gray-700 border border-gray-500 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="text" placeholder="Nama">
    </div>
    <div class="w-full md:w-1/2 px-3">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
        Last Name
      </label>
      <input class="appearance-none block w-48 sm:w-full bg-gray-200 text-gray-700 border border-gray-500 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Nama">
    </div>
  </div>
  <div class="sm:flex flex-wrap -mx-3 mb-2">
    <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-city">
        City
      </label>
      <input class="appearance-none block w-48 sm:w-full bg-gray-200 text-gray-700 border border-gray-500 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-city" type="text" placeholder="Malang">
    </div>
    <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-state">
        State
      </label>
      <div class="relative">
        <select class="block appearance-none w-48 sm:w-full bg-gray-200 border border-gray-500 text-gray-700 py-3 px-4 pr-8 rounded leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-state">
          <option>Jawa Timur</option>
          <option>Jawa Barat</option>
          <option>Jawa Tengah</option>
        </select>
        <div class="pointer-events-none absolute inset-y-0 sm:right-0 flex items-center px-2 text-gray-700">
          <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
        </div>
      </div>
    </div>
    <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-zip">
        Zip
      </label>
      <input class="appearance-none block w-48 sm:w-full bg-gray-200 text-gray-700 border border-gray-500 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-zip" type="text" placeholder="42415">
    </div>
  </div>
  <button class="btn-primary bg-deepsea hover:bg-breaker text-sm p-2 m-5 rounded-full w-32 text-white">Submit</button>
</form>
      </div>
    </div>
  </div>
  <div class="footer-section flex flex-col h-32 bg-botticelli-darker justify-center items-center">
      <div class="icon-container inline-flex p-2">
        <img src="../assets/instagram.svg" class="w-6 mx-5">
        <img src="../assets/twitter.svg" class="w-6 mx-5">
        <img src="../assets/facebook.svg" class="w-6 mx-5">
      </div>
      <div class="footer text-center inline-flex justify-center bg-transparent p-2">
      <p class="font-thin text-gray-900">© 2020 Copyright: </p><p class="font-base text-white ml-1"> Sea.com</p>
      </div>
  </div>
</div>
</template>

<script>
import gsap from 'gsap'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    anim1 (lr) {
      gsap.fromTo(lr, 1.3, {
        opacity: '0',
        x: -100
      }, {
        opacity: '100%',
        x: 0,
        ease: 'power2.out'
      })
    }
  },
  anim2 (tx) {
    gsap.fromTo(tx, 1.5, {
      opacity: '0%',
      x: 100
    }, {
      opacity: '100%',
      x: 0,
      ease: 'power2.out'
    })
  }
}
</script>
