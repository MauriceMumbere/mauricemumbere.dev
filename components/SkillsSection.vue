<template>
  <section
    id="skills"
    class="min-h-screen flex items-center px-4 py-16 sm:px-8 lg:px-[280px]"
  >
    <div class="max-w-7xl mx-auto">
      <!-- Titres -->
      <div class="text-center lg:text-left">
        <h3 class="uppercase text-base sm:text-lg pb-2">Compétences</h3>
        <h2 class="text-3xl sm:text-4xl lg:text-5xl font-bold pb-12">
          Ce que je vous apporte
        </h2>
      </div>

      <!-- Grille -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-20">
        <!-- Compétences techniques -->
        <div>
          <div class="flex items-center gap-3 pb-7">
            <div class="bg-green-500 h-3 w-3 rounded-full"></div>
            <h3 class="text-lg">Compétences techniques</h3>
          </div>

          <div class="flex flex-wrap gap-4">
            <!-- Exemple d’item (le reste ne change pas) -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl text-sm sm:text-base"
            >
              <img
                src="/assets/icons/javascript-icon.svg"
                alt="Javascript"
                class="w-4 h-4"
              />
              Javascript
            </div>
            <!-- Typescript -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/typescript-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Typescript
            </div>
            <!-- Vuejs -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/vuejs-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Vuejs
            </div>
            <!-- Nuxt -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/nuxt-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Nuxt
            </div>
            <!-- Tailwindcss -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/tailwindcss-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Tailwindcss
            </div>
            <!-- Expressjs -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/expressjs-icon.svg"
                alt="Tailwind CSS icon"
                class="w-5 h-5 transition-transform duration-300 group-hover:scale-110"
              />
              Expressjs
            </div>
            <!-- Adonisjs -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/adonisjs-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Adonisjs
            </div>
            <!-- Nodjs -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/nodejs-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Nodjs
            </div>
            <!-- Postgresql -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/postgresql-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Postgresql
            </div>
            <!-- Git -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/git-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Git
            </div>
            <!-- Github -->
            <div
              class="flex items-center gap-2 border border-black/40 px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/github-icon.svg"
                alt="Tailwind CSS icon"
                class="w-5 h-5 transition-transform duration-300 group-hover:scale-110"
              />
              Github
            </div>
            <!-- Flutter -->
            <div
              class="flex items-center gap-2 border border-black/40 hover:border-black transition-colors px-3 py-2 rounded-2xl"
            >
              <img
                src="/assets/icons/flutter-icon.svg"
                alt="Tailwind CSS icon"
                class="w-4 h-4 transition-transform duration-300 group-hover:scale-110"
              />
              Flutter
            </div>
          </div>
        </div>

        <!-- Savoir-être -->
        <div>
          <div class="flex items-center gap-3 pb-7">
            <div class="bg-green-500 h-3 w-3 rounded-full"></div>
            <h3 class="text-lg">Savoir-être</h3>
          </div>

          <div class="flex flex-wrap gap-4">
            <div
              class="border border-amber-100 px-3 py-2 rounded-2xl text-sm sm:text-base"
            >
              Travail d'équipe
            </div>
            <div
              class="border border-amber-100 px-3 py-2 rounded-2xl text-sm sm:text-base"
            >
              Souci du détail
            </div>
            <div
              class="border border-amber-100 px-3 py-2 rounded-2xl text-sm sm:text-base"
            >
              Adaptabilité
            </div>
            <div
              class="border border-amber-100 px-3 py-2 rounded-2xl text-sm sm:text-base"
            >
              Résolution des problèmes
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
