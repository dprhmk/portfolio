<script setup></script>

<template>
  <div class="container m-auto">
    <div class="relative m-10 border border-slate-100 rounded-3xl p-8 shadow-xl">
      <div class="flex mb-4">
        <div class="w-1/2 sm:w-4/12 px-4">
          <img
            class="box-border rounded-full border-4 border-sky-500"
            src="/media/photo.jpg"
            alt="user-photo"
          />
        </div>
        <div class="w-2/3 text-left ml-8">
          <h1 class="text-5xl font-extrabold">
            <span class="hand-greeting">👋</span>
            Hi, I'm
            <span
              class="bg-gradient-to-r from-emerald-400 via-sky-400 to-indigo-400 inline-block text-transparent bg-clip-text"
            >
              Dima
            </span>
          </h1>
          <h2 class="pt-4 text-2xl font-bold">I'm a Laravel & Nuxt Developer</h2>
          <ul class="pt-4 text-base">
            <li class="pt-2">
              <span class="text-2xl mr-4" role="img">🌎</span>
              based in Khmelnytskyi, Ukraine
            </li>
            <li class="pt-2">
              <span class="text-2xl mr-4" role="img">💼</span> BackEnd Developer at ArtSites Studio
            </li>
            <li>
              <span class="text-2xl mr-4" role="img">📅</span>
              3 years of experience in Laravel development and deployment
            </li>
            <li class="pt-2">
              <span class="text-2xl mr-4" role="img">📧</span>
              dprhmk@gmail.com
            </li>
            <li class="pt-2"><span class="text-3xl mr-4" role="img">📞</span> +38 098-***-****</li>
          </ul>
          <div class="text-5xl pt-4">
            <a
              class="mr-8"
              target="_blank"
              aria-label="github"
              rel="noopener noreferrer"
              href="https://github.com/dprhmk"
              ><i class="fa fa-github" aria-hidden="true"></i></a
            ><a
              target="_blank"
              aria-label="linkedin"
              rel="noopener noreferrer"
              href="https://www.linkedin.com/in/dima-pryimak-5a46b2213/"
              ><i class="fa fa-linkedin" aria-hidden="true"></i
            ></a>
            <div class="pt-4">
              <a
                target="_blank"
                href="dima_pryimak_cv.pdf"
                class="bg-white hover:bg-gray-100 text-gray-800 font-semibold py-2 px-4 border border-gray-400 rounded shadow text-base"
              >
                Download CV
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.hand-greeting {
  animation-name: wave-animation; /* Refers to the name of your @keyframes element below */
  animation-duration: 2.5s; /* Change to speed up or slow down */
  animation-iteration-count: infinite; /* Never stop waving :) */
  transform-origin: 70% 70%; /* Pivot around the bottom-left palm */
  display: inline-block;
}

@keyframes wave-animation {
  0% {
    transform: rotate(0deg);
  }
  10% {
    transform: rotate(14deg);
  } /* The following five values can be played with to make the waving more or less extreme */
  20% {
    transform: rotate(-8deg);
  }
  30% {
    transform: rotate(14deg);
  }
  40% {
    transform: rotate(-4deg);
  }
  50% {
    transform: rotate(10deg);
  }
  60% {
    transform: rotate(0deg);
  } /* Reset for the last half to pause */
  100% {
    transform: rotate(0deg);
  }
}
</style>
