<template>
    <nav class="flex items-center justify-between flex-wrap bg-indigo-950 opacity-80  p-3 fixed w-full z-10 top-0 shadow-lg backdrop-blur-xl backdrop-filter">
    <div class="flex items-center flex-shrink-0 text-white ml-12 text-lg">
        <img class="logonav"src="public/JyLogo-White.png">
        <p>CREATIVES</p>
    </div>

    <label for="menu-toggle" class="pointer-cursor md:hidden block">
      <svg class="fill-current text-gray-900"
        xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20">
        <title>menu</title>
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
      </svg>
    </label>
    <input class="hidden" type="checkbox" id="menu-toggle" />

    <div class="hidden md:flex md:items-center md:w-auto w-full" id="menu">
        <nav>
            <ul class="md:flex items-center justify-between text-base text-white pt-4 md:pt-0 text-xl gap-1 font-bold">
                <li><a class="md:p-4 py-3 px-0 block" href="#Home">HOME</a></li>
                <li><a class="md:p-4 py-3 px-0 block" href="#About">ABOUT</a></li>
                <li><a class="md:p-4 py-3 px-0 block" href="#Project">PROJECTS</a></li>
                <li><a class="md:p-4 py-3 px-0 block md:mb-0 mb-2" href="#Contact">CONTACT US</a></li>
            </ul>
        </nav>
    </div>
</nav>
</template>