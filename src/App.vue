<template>
  <header class="text-white">
    <div
      class="max-w-screen-xl mx-auto flex flex-wrap py-5 flex-col md:flex-row items-center"
    >
      <a class="flex title-font font-bold items-center text-white mb-4 md:mb-0">
        <img
          class="h-10 mr-3"
          src="https://uploads-ssl.webflow.com/5de176bfd41c9b0a91bbb0a4/5de17d653719a1f46cdb62ae_image%20(3).png"
          alt=""
        />
        <span class="ml-3 text-xl">Qovery</span>
      </a>
      <nav
        class="md:mr-auto md:ml-4 md:py-1 md:pl-4 flex flex-wrap items-center text-sm justify-center"
      >
        <a class="mr-5">Home</a>
        <a class="mr-5">Pricing</a>
        <a class="mr-5">Community</a>
        <a class="mr-5">Blog</a>
      </nav>
      <button
        class="inline-flex items-center bg-transparant border-2 py-2 px-5 focus:outline-none rounded text-sm mt-4 mr-5 md:mt-0 uppercase"
      >
        Documentation
      </button>
      <button
        class="inline-flex items-center bg-gray-200 border-2 py-2 px-5 focus:outline-none rounded text-sm text-violet-500 mt-4 mr-5 md:mt-0 uppercase"
      >
        Sign up
      </button>
    </div>
  </header>
  <section id="hero" class="text-white body-font">
    <div
      class="max-w-screen-xl mx-auto flex py-24 md:flex-row flex-col items-center"
    >
      <div
        class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
      >
        <div
          class="mb-4 py-1 px-1.5 bg-coolGray-800 font-normal text-xs text-gray-400 rounded uppercase"
        >
          Superpowers for tech companies
        </div>
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-bold text-white">
          The simplest way to deploy your
          <br class="hidden lg:inline-block" />full-stack apps
        </h1>
        <p class="mb-8 leading-relaxed text-white text-2xl">
          Push your code, Qovery handles the rest
        </p>
        <div class="flex justify-center items-center">
          <button
            class="inline-flex text-white bg-indigo-700 py-3 px-6 focus:outline-none transition duration-500 ease-in-out transform hover:-translate-y-2 hover:bg-indigo-600 rounded font-medium text-sm uppercase"
          >
            Deploy my application
          </button>
          <button
            class="ml-4 inline-flex text-white bg-transparant border-2 border-white py-3 px-6 focus:outline-none transition duration-500 ease-in-out transform hover:-translate-y-2 rounded font-medium text-sm uppercase"
          >
            Documentation
          </button>
        </div>
        <span class="mt-4 text-sm text-gray-400"
          >Qovery is free for individual developer. Give a try now!</span
        >
      </div>
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
        <img
          class="object-cover object-center"
          alt="hero"
          src="https://uploads-ssl.webflow.com/5de176bfd41c9b0a91bbb0a4/5fbee06391639836fcaddf45_deploy_to_aws_only.svg"
        />
      </div>
    </div>
    <div class="flex flex-col items-center">
      <div class="text-sm text-gray-400 uppercase">
        Developers from great companies trust us
      </div>
      <div class="flex mt-12 mb-20">
        <a href="#">
          <img
            class="h-10 mr-12 transition duration-500 ease-in-out opacity-60 hover:opacity-100"
            src="https://uploads-ssl.webflow.com/5de176bfd41c9b0a91bbb0a4/5fbe983f1b155c154a7526e2_qonto-p-500.png"
            alt=""
          />
        </a>
        <a href="#">
          <img
            class="h-10 mr-12 transition duration-500 ease-in-out opacity-60 hover:opacity-100"
            src="https://uploads-ssl.webflow.com/5de176bfd41c9b0a91bbb0a4/5fb90dc0d2fdf172e6cb6945_spendesk-p-500.png"
            alt=""
          />
        </a>
        <a href="#">
          <img
            class="h-10 mr-12 transition duration-500 ease-in-out opacity-60 hover:opacity-100"
            src="https://uploads-ssl.webflow.com/5de176bfd41c9b0a91bbb0a4/5fbec6cb10a4437624f3f082_aircall_white-p-500.png"
            alt=""
          />
        </a>
        <a href="#">
          <img
            class="h-10 mr-12 transition duration-500 ease-in-out opacity-60 hover:opacity-100"
            src="https://uploads-ssl.webflow.com/5de176bfd41c9b0a91bbb0a4/5fb90db393a2e7d673210dc2_contentsquare-p-500.png"
            alt=""
          />
        </a>
        <a href="#">
          <img
            class="h-10 transition duration-500 ease-in-out opacity-60 hover:opacity-100"
            src="https://uploads-ssl.webflow.com/5de176bfd41c9b0a91bbb0a4/5fb910d15fb8453150e5987d_helios-p-500.png"
            alt=""
          />
        </a>
      </div>
    </div>
  </section>
  <section class="bg-white text-white body-font">
    <div
      class="container mx-auto flex py-24 md:flex-row flex-col items-center"
    ></div>
  </section>
</template>

<script>
export default {
  name: "App",
};
</script>
