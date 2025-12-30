<script setup></script>

<template>
  <section
    id="contact"
    class="px-4 py-16 sm:px-8 sm:py-24 lg:px-[280px] lg:py-32"
  >
    <div class="max-w-6xl mx-auto">
      <!-- Titres -->
      <div class="text-center lg:text-left">
        <h3 class="uppercase pb-2 text-sm sm:text-base">Me contacter</h3>
        <h2 class="text-3xl sm:text-4xl font-bold pb-12">
          On discute de votre projet
        </h2>
      </div>

      <!-- Contenu -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
        <!-- Texte + email -->
        <div class="space-y-6">
          <p class="text-sm sm:text-base leading-relaxed">
            Vous avez un projet web ou mobile et cherchez un développeur motivé,
            rigoureux et à l’écoute ? Je vous accompagne dans la création de
            solutions simples, modernes et adaptées à vos besoins.
          </p>

          <div class="flex flex-col sm:flex-row sm:items-center gap-4 sm:gap-8">
            <a href="#" class="flex items-center gap-2">
              <img
                src="/assets/icons/tailwindcss-icon.svg"
                alt="Email"
                class="w-4 h-4"
              />
              <span class="break-all"> mauricendayango@gmail.com </span>
            </a>

            <button
              class="text-sm border border-black px-4 py-1 rounded-full w-fit"
            >
              Copier
            </button>
          </div>
        </div>

        <!-- Réseaux -->
        <div
          class="bg-gray-100 rounded-2xl p-6 sm:p-8 max-w-sm mx-auto lg:mx-0"
        >
          <h3 class="mb-4 text-black font-semibold text-center lg:text-left">
            Mes réseaux
          </h3>

          <div class="space-y-4">
            <a
              href="#"
              class="flex items-center justify-center gap-2 py-2 rounded-2xl border border-black"
            >
              <img
                src="/assets/icons/tailwindcss-icon.svg"
                alt="LinkedIn"
                class="w-4 h-4"
              />
              <span class="text-black">LinkedIn</span>
            </a>

            <a
              href="#"
              class="flex items-center justify-center gap-2 py-2 rounded-2xl border border-black"
            >
              <img
                src="/assets/icons/tailwindcss-icon.svg"
                alt="Github"
                class="w-4 h-4"
              />
              <span class="text-black">GitHub</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
