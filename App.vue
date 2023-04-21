<script setup>

</script>

<template>
  <!-- navbar -->
  <header>
    <nav class="bg-white border-gray-200 px-4 lg:px-6 py-2.5 dark:bg-gray-800">
      <div class="flex flex-wrap justify-between items-center mx-auto max-w-screen-xl">
        <a href="#" class="flex items-center">
          <img src="./assets/img/viggologo.png" class="mr-3 h-6 sm:h-9" alt="Flowbite Logo" />

        </a>
        <div class="flex items-center lg:order-2">
          <button data-collapse-toggle="mobile-menu-2" type="button"
            class="inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg lg:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
            aria-controls="mobile-menu-2" aria-expanded="false">
            <span class="sr-only">Open main menu</span>
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd"
                d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                clip-rule="evenodd"></path>
            </svg>
            <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd"
                d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                clip-rule="evenodd"></path>
            </svg>
          </button>
        </div>
        <div class="hidden justify-between items-center w-full lg:flex lg:w-auto lg:order-1" id="mobile-menu-2">
          <ul class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0">
            <li>
              <a href="#"
                class="block py-2 pr-4 pl-3 text-white rounded bg-primary-700 lg:bg-transparent lg:text-primary-700 lg:p-0 dark:text-white"
                aria-current="page">Hjem</a>
            </li>
            <li>
              <a href="#"
                class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Om
                mig</a>
            </li>
            <li>
              <a href="#"
                class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Portfolio</a>
            </li>
            <li>
              <a href="#"
                class="block py-2 pr-4 pl-3 text-gray-700 border-b border-gray-100 hover:bg-gray-50 lg:hover:bg-transparent lg:border-0 lg:hover:text-primary-700 lg:p-0 dark:text-gray-400 lg:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white lg:dark:hover:bg-transparent dark:border-gray-700">Kompetencer</a>
            </li>

          </ul>
        </div>
      </div>
    </nav>
  </header>
  <!-- navbarslut-->

  <!-- herostart -->
  <section class="bg-white dark:bg-gray-900">
    <div class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12">
      <div class="mr-auto place-self-center lg:col-span-7">
        <h1
          class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white">
          Victor Henriksen</h1>
        <p class="max-w-2xl mb-6 font-bold text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400">Student on EASV
          Multemedie designer</p>
        <a href="#"
          class="inline-flex items-center justify-center px-5 py-3 mr-3 text-base font-medium text-center text-white rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900">
          Hvem er jeg?
        </a>
        <a href="https://www.dropbox.com/s/rgrvdca7pug5lsh/Sk%C3%A6rmbillede%202023-04-20%20135732.png?dl=0"
          class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800">
          Hent CV
        </a>
      </div>
      <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
        <img class="rounded-full drop-shadow-2xl" src="./assets/img/hero.jpg" alt="mockup">
      </div>
    </div>
  </section>
  <!-- heroslut -->

  <!-- kompetencer start -->
  <section>
    <div class="bg-white py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="mx-auto max-w-2xl sm:text-center">
          <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Kompetencer</h2>
        </div>
        <div class="mx-auto mt-16 max-w-2xl rounded-3xl ring-1 ring-gray-200 sm:mt-20 lg:mx-0 lg:flex lg:max-w-none">
          <div class="p-8 sm:p-10 lg:flex-auto">
            <div class="chroma flex space-x-2">
              <svg aria-hidden="true" class=" w-5 e-font-icon-svg e-fas-pencil-ruler" fill="#1d4ed8" viewBox="0 0 512 512"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M109.46 244.04l134.58-134.56-44.12-44.12-61.68 61.68a7.919 7.919 0 0 1-11.21 0l-11.21-11.21c-3.1-3.1-3.1-8.12 0-11.21l61.68-61.68-33.64-33.65C131.47-3.1 111.39-3.1 99 9.29L9.29 99c-12.38 12.39-12.39 32.47 0 44.86l100.17 100.18zm388.47-116.8c18.76-18.76 18.75-49.17 0-67.93l-45.25-45.25c-18.76-18.76-49.18-18.76-67.95 0l-46.02 46.01 113.2 113.2 46.02-46.03zM316.08 82.71l-297 296.96L.32 487.11c-2.53 14.49 10.09 27.11 24.59 24.56l107.45-18.84L429.28 195.9 316.08 82.71zm186.63 285.43l-33.64-33.64-61.68 61.68c-3.1 3.1-8.12 3.1-11.21 0l-11.21-11.21c-3.09-3.1-3.09-8.12 0-11.21l61.68-61.68-44.14-44.14L267.93 402.5l100.21 100.2c12.39 12.39 32.47 12.39 44.86 0l89.71-89.7c12.39-12.39 12.39-32.47 0-44.86z">
                </path>
              </svg>
              <h3 class="text-2xl font-bold tracking-tight text-gray-900">UI/UX Designer</h3>
            </div>
            <p class="mt-6 text-base leading-7 text-gray-600">En effektiv UI/UX er det, der fanger opmærksomheden og
              spreder et klart budskab. Jeg sørger for, at designet er innovativt og pænt med alt dette.</p>
          </div>
          <div class="p-8 sm:p-10 lg:flex-auto">
            <div class="chroma flex space-x-2">
              <svg aria-hidden="true" class="w-5 e-font-icon-svg e-fas-video" fill="#1d4ed8" viewBox="0 0 576 512"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M336.2 64H47.8C21.4 64 0 85.4 0 111.8v288.4C0 426.6 21.4 448 47.8 448h288.4c26.4 0 47.8-21.4 47.8-47.8V111.8c0-26.4-21.4-47.8-47.8-47.8zm189.4 37.7L416 177.3v157.4l109.6 75.5c21.2 14.6 50.4-.3 50.4-25.8V127.5c0-25.4-29.1-40.4-50.4-25.8z">
                </path>
              </svg>
              <h3 class="text-2xl font-bold tracking-tight text-gray-900">VIDEOGRAPHER</h3>
            </div>
            <p class="mt-6 text-base leading-7 text-gray-600">Ud fra et teknisk synspunkt kan videografi defineres som den
              elektroniske optagelse af levende billeder på elektroniske medier - herunder specifikke videoredigering og
              postproduktionsmetoder.
            </p>
          </div>
          <div class="p-8 sm:p-10 lg:flex-auto">
            <div class="chroma flex space-x-2">
              <svg aria-hidden="true" class="w-5 e-font-icon-svg e-fas-edit" fill="#1d4ed8" viewBox="0 0 576 512"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M402.6 83.2l90.2 90.2c3.8 3.8 3.8 10 0 13.8L274.4 405.6l-92.8 10.3c-12.4 1.4-22.9-9.1-21.5-21.5l10.3-92.8L388.8 83.2c3.8-3.8 10-3.8 13.8 0zm162-22.9l-48.8-48.8c-15.2-15.2-39.9-15.2-55.2 0l-35.4 35.4c-3.8 3.8-3.8 10 0 13.8l90.2 90.2c3.8 3.8 10 3.8 13.8 0l35.4-35.4c15.2-15.3 15.2-40 0-55.2zM384 346.2V448H64V128h229.8c3.2 0 6.2-1.3 8.5-3.5l40-40c7.6-7.6 2.2-20.5-8.5-20.5H48C21.5 64 0 85.5 0 112v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V306.2c0-10.7-12.9-16-20.5-8.5l-40 40c-2.2 2.3-3.5 5.3-3.5 8.5z">
                </path>
              </svg>
              <h3 class="text-2xl font-bold tracking-tight text-gray-900">VIDEO EDITER</h3>
            </div>
            <p class="mt-6 text-base leading-7 text-gray-600">Videoredigering er den proces, hvorved rå filmmateriale
              behandles og gøres præsentationsklart. Under redigeringen fraklippes det uønskede materiale, og det
              tilbageværende sammensættes i den ønskede kronologiske rækkefølge.</p>
          </div>
        </div>
      </div>
    </div>
</section>
<!-- kompetencer slut -->
<!-- cv video start -->
<section>
<div class="mx-auto max-w-2xl sm:text-center">
          <h2 class="text-3xl font-bold tracking-tight my-10 text-gray-900 sm:text-4xl">CV Video</h2>
        </div>
<div class=" flex justify-center h-96">
  
    <img class="w-full relative z-0 opacity-70" src="https://images.pexels.com/photos/303383/pexels-photo-303383.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
    <a href="https://www.youtube.com/watch?v=rr-T8UaKZ0U"
          class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800">
          Hent Video
        </a>

</div>
</section>
<!-- cv video slut -->
<section>
  <div class="mx-auto max-w-2xl sm:text-center">
          <h2 class="text-3xl font-bold tracking-tight my-10 text-gray-900 sm:text-4xl">Portfolio</h2>
        </div>
<div class="rasmusharingenchroma flex justify-evenly my-20">
  <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
    <a href="#">
        <img class="rounded-t-lg" src="./assets/img/festival.png" alt="" />
    </a>
    <div class="p-5">
        <a href="#">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Radiant festival</h5>
        </a>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Her har jeg lavet et event til at få flere mennseker til esbjerg, hvor der så lagt fokus på at holde et stort event årligt i Esbjerg</p>
    </div>
</div>

<div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
    <a href="#">
        <img class="rounded-t-lg" src="./assets/img/BBQ.png" alt="" />
    </a>
    <div class="p-5">
        <a href="#">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">BBQ Event/hjemmeside</h5>
        </a>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">BBQ event blev lavet fordi vi skulle optimere deres event hjemmeside samt at få et større kendskab til selve eventet </p>
       
    </div>
</div>

<div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
    <a href="#">
        <img class="rounded-t-lg" src="./assets/img/efapaint.jpg" alt="" />
    </a>
    <div class="p-5">
        <a href="#">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">EFA PAINT KAMPAGNE</h5>
        </a>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">EFA PAINT blevet lavet via mit arbejde, hvor blandt andet står for soMe og meget andet, heriblandt blev der så lavet en kampagne</p>
    </div>
</div>

</div>

<div class="rasmusharingenchroma flex justify-evenly my-20">
  <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
    <a href="#">
        <img class="rounded-t-lg" src="./assets/img/viggo.jpg" alt="" />
    </a>
    <div class="p-5">
        <a href="#">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Billede Redigering</h5>
        </a>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Det her billede er lavet i sammearbejde med den hjemmeside jeg lavet via ekstemsport</p>
    </div>
</div>

<div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
    <a href="#">
        <img class="rounded-t-lg" src="./assets/img/card123.jpg" alt="" />
    </a>
    <div class="p-5">
        <a href="#">
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Businesscard</h5>
        </a>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Her er mit businesskort som du kan se ved at kikke på hent businesskort </p>
        <a href="https://www.dropbox.com/s/uyoxhlxcphh2xmf/kort.pdf?dl=0"
          class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800">
          Hent Bussinesscard
        </a>
    </div>
</div>

</div>
</section>
</template>

<style scoped></style>
