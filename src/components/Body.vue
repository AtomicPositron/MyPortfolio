<template>
  <div id="underline" class="w-6/12 h-1 opacity-60 rounded bg-[#ffffff] "></div>
  <div id="mainBody" class="flex justify-center items-center flex-col ">
    <h1 class="font-bold text-7xl text-center p-10">My Projects</h1>
    <div class="xl:w-6/12 w-10/12 flex xl:flex-row flex-col gap-10 mt-20">
      <div id="img" class="flex items-center flex-col gap-10">
        <div id="projectGradient" class="w-[27rem] relative h-70 before:absolute before:top-0 before:left-0 before:w-full before:h-full before:bg-gradient-to-b before:from-transparent before:to-black ">
          <img src="../../Projectimage.png" class="object-cover h-80" alt="projectImage"> 
        </div>
        <a href="https://github.com/MichaelIbia12/animeDiscovery">
  <button class="bg-[#304439] hover:bg-white transition-all hover:text-black p-3 rounded w-40">Github Repository</button>
        </a>
      </div>
<!--TODO: Fix radial-gradient for text div-->

      <div class="xl:w-auto w-96">
        <h4 class="text-lg font-bold">Anime Discovery</h4>
        <p>Anime Discovery is a web application that helps users explore anime based on their favorite genres. Built
          with NEXT.js and styled using Tailwind, the app leverages the kitsu.io API to fetch anime data. Simply enter a
          genre in the input box, and the app displays matching anime titles as visually appealing cards. It's a sleek,
          user-friendly tool for anime enthusiasts to discover new shows.
        </p>
      </div>
    </div>
    <button class="mt-36 bg-[#1E1E1E] transition-all hover:bg-black w-40 rounded-lg p-5">See more</button>
  <div id="underline" class="w-6/12 mt-36 h-1 opacity-60 rounded bg-[#ffffff] "></div>
  
  </div>
</template>
