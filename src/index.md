---
layout: layouts/default.njk
title: Octopus Maps Home
---

<section class= "flex pt-8 justify-center">
  <h1 class="text-3xl font-bold">Our Research</h1>
</section>

<div class="flex flex-row w-dvw py-16 px-[min(5vw,40)] justify-center items-center place-content-between -space-x-20 translate-x-105">
    <div class="order-4 peer/swiper4 group bg-[url(./assets/img/guerre.webp)] swiper
    bg-gray-300 bg-blend-multiply transition-transform duration-300 ease-in-out 
    scale-82 -translate-x-130 
    hover:scale-100 
    peer-hover/swiper1:scale-70 
    peer-hover/swiper3:scale-95 peer-hover/swiper3:z-20
    z-10 hover:z-40">
     <a href="#" class="absolute w-full h-full top-0 left-0 rounded-3xl bg-linear-to-t from-gray-900 to-gray-50/0 opacity-0 transition-opacity duration-300 hover:opacity-40 z-40">
     </a>
     <h6 class="absolute text-white bottom-4 left-4 opacity-0 transition duration-300 ease-in-out group-hover:opacity-100 z-40">
       Dataset
     </h6>

      <!-- Because I used the background function instead of images, I used "sr-only" to add the alt texts. -->
     <span class="sr-only">Image: an octopus map made in 1920s with rich cartographic information.</span>
   </div>

    <div class="order-1 peer/swiper1 group bg-[url(./assets/img/polyp.webp)] swiper
    bg-gray-300 bg-blend-multiply 
    transition-transform duration-300 ease-in-out 
    scale-90 hover:scale-100
    peer-hover/swiper4:scale-70 peer-hover/swiper4:z-10
    z-30 hover:z-40">
      <a href="#" class="absolute w-full h-full top-0 left-0 rounded-3xl bg-linear-to-t from-gray-900 to-gray-50/0 opacity-0 transition-opacity duration-300 hover:opacity-40 z-20">
      </a>
      <h6 class="absolute text-white bottom-4 left-4 opacity-0 transition duration-300 ease-in-out group-hover:opacity-100 z-20">
        Full Article
      </h6>
      <span class="sr-only">Image: a German poster with the octopus and Isranian warrior battling on a globe.</span>
    </div>

    <div class="order-3 peer/swiper3 group bg-[url(./assets/img/curse.webp)] swiper
    bg-gray-300 bg-blend-multiply transition-transform duration-300 ease-in-out 
    scale-90 -translate-x-80 hover:scale-100 
    peer-hover/swiper1:scale-80 
    peer-hover/swiper4:scale-90 peer-hover/swiper4:z-30
    z-20 hover:z-40">
      <a href="#" class="absolute w-full h-full top-0 left-0 rounded-3xl bg-linear-to-t from-gray-900 to-gray-50/0 opacity-0 transition-opacity duration-300 hover:opacity-40 z-40">
      </a>
      <h6 class="absolute text-white bottom-4 left-4 opacity-0 transition duration-300 ease-in-out group-hover:opacity-100 z-40">
        Conceptual Metaphors in Octopus Maps
      </h6>
      <span class="sr-only">Image: a cover of a fantasy novel created in the late 19th century, with a giant octopus attacking the ship.</span>
    </div>

    <div class="order-2 peer/swiper2 group bg-[url(./assets/img/serio.webp)] swiper
     bg-gray-300 bg-blend-multiply  
     transition-transform duration-300 ease-in-out 
     scale-100 -translate-x-40 hover:scale-100
     peer-hover/swiper1:z-30 peer-hover/swiper1:scale-90 
     peer-hover/swiper3:scale-95 peer-hover/swiper3:z-30
     peer-hover/swiper4:scale-80 peer-hover/swiper4:z-20
     z-40 hover:z-40">
      <a href="#" class="absolute w-full h-full top-0 left-0 rounded-3xl bg-linear-to-t from-gray-900 to-gray-50/0 opacity-0 transition-opacity duration-300 hover:opacity-60 z-30">
      </a>
      <h6 class="absolute text-white bottom-4 left-4 opacity-0 transition duration-300 ease-in-out group-hover:opacity-100 z-40">
        Browse the Full Corpus
      </h6>
      <span class="sr-only">Image: A famous octopus map by F.W. Rose in 1870, with the Russian depicted as an giant octopus on the top of the map, and the other European countries are depicted as different people.</span>
    </div>
</div>

<section
  class="hero min-h-150"
  style="background-image: url(./assets/img/dollar.webp);"
>
  <div class="hero-overlay bg-neutral/80"></div>
  <div class="hero-content flex-col px-12 space-y-5">
    <div>
      <h1 class="text-3xl font-bold text-base-100">Octopus Game</h1>
    </div>
    <div class="card card-side bg-base-100/90 shadow-sm">
      <figure class="w-1/2">
        <img
          src="assets/img/similarity.gif"
          alt="A gif capture about the octopus game" />
      </figure>
      <div class="card-body w-1/2 p-12 lg:p-24">
        <h2 class="card-title lg:text-4xl">Visual Similarity of Octopus Maps</h2>
        <p>There are certain similarity between the octopus maps. Using our corpus, we drew on the current deep learning model and analyze the visual similarity between the octopus maps. Explore with us!</p>
        <div class="justify-end card-actions">
          <button class="btn btn-primary">Explore!</button>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="bg-linear-to-b from-gray-400 to-gray-50/0 py-8">
  <div class= "flex pt-8 justify-center">
    <h1 class="text-3xl font-bold text-base-100">Feature Examples</h1>
  </div>
  <div class="grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 p-12">
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/humorous.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">A Humorous Diplomatic Atlas of Europe and Asia</h2>
        <p>1904</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/john.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">John Bull and His Friends</h2>
        <p>1900</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/dollar.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">The Dollar Octopus</h2>
        <p>1943</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/danger.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">Recognize the danger! Vote for the Austrian People's Party</h2>
        <p>1949</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/allies.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">Allies Loosen Grip of Nazi Octopus </h2>
        <p>1941</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/barbarians.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">Before the Barbarians. The United States and the War</h2>
        <p>1918</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/revenge.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">Revenge</h2>
        <p>1886</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
    <article class="card bg-base-100 shadow-sm transition-all ease-in-out hover:-translate-0.5 hover:shadow-2xl">
      <figure href="#">
        <img
          class="aspect-1/1 object-cover transition-transform ease-in-out hover:scale-105"
          src="assets/img/british.webp"
          alt="war" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">The Red Octopus</h2>
        <p>1980</p>
              <div class="card-actions justify-end">
        <button class="btn btn-soft btn-sm">Read More</button>
      </div>
      </div>
    </article>
  </div>
  <div class="flex justify-center">
    <btn class="btn btn-secondary btn-wide">Full Corpus</btn>
  </div>
</section>