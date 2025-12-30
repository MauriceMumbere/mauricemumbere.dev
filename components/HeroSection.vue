<template>
  <div class="hero bg-base-200 min-h-screen px-4 md:px-12 lg:px-[250px]">
    <div
      class="hero-content justify-between w-full flex-col lg:flex-row-reverse"
    >
      <img
        src="https://img.daisyui.com/images/stock/photo-1635805737707-575885ab0820.webp"
        class="w-[400px] rounded-lg shadow-2xl"
      />
      <div class="space-y-5">
        <h3
          class="text-sm uppercase tracking-widest text-primary font-semibold"
        >
          Hello
        </h3>
        <h2 class="text-2xl">Developpeur web et mobile</h2>
        <h1 class="text-4xl md:text-5xl font-bold leading-tight">
          Maurice Mumbere
        </h1>
        <div class="flex space-x-4">
          <a
            href="#"
            class="flex items-center gap-2 border border-black/40 rounded-2xl p-[10px]"
          >
            <img
              src="/assets/icons/tailwindcss-icon.svg"
              alt="Tailwind CSS icon"
              class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
            />
            Gmail
          </a>
          <a
            href="#"
            class="flex items-center gap-2 border border-black/40 rounded-2xl p-[10px]"
          >
            <img
              src="/assets/icons/tailwindcss-icon.svg"
              alt="Tailwind CSS icon"
              class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
            />
            Linkedin
          </a>
          <a
            href="#"
            class="flex items-center gap-2 border border-black/40 rounded-2xl p-[10px]"
          >
            <img
              src="/assets/icons/tailwindcss-icon.svg"
              alt="Tailwind CSS icon"
              class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
            />
            Github
          </a>
        </div>
        <div>
          <a
            href="/assets/resume.pdf"
            download
            class="btn bg-green-300 w-full md:w-[400px] px-[10px] py-[20px]"
          >
            Download Resume
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
