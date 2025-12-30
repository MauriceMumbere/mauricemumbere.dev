<template>
  <section
    id="about"
    class="bg-base-200 min-h-screen px-4 py-35 sm:px-8 lg:px-24"
  >
    <div
      class="mx-auto max-w-6xl grid grid-cols-1 lg:grid-cols-2 gap-12 items-center"
    >
      <!-- Image -->
      <div class="flex justify-center">
        <img
          src="https://img.daisyui.com/images/stock/photo-1635805737707-575885ab0820.webp"
          alt="Photo de présentation"
          class="w-full max-w-sm rounded-2xl shadow-2xl object-cover"
        />
      </div>

      <!-- Texte -->
      <div class="space-y-6 text-center lg:text-left">
        <div>
          <h3 class="uppercase tracking-widest text-sm text-primary pb-2">
            À propos
          </h3>
          <h2 class="text-3xl sm:text-4xl font-bold">Qui je suis</h2>
        </div>

        <p class="text-base leading-relaxed text-gray-600">
          Développeur full-stack passionné par la création d'applications web
          modernes. Formé à la Wild Code School, je maîtrise aussi bien le
          backend que le frontend.
        </p>

        <p class="text-base leading-relaxed text-gray-600">
          Anciennement préparatrice en pharmacie, j'ai développé une grande
          rigueur et une attention aux détails que j'applique aujourd'hui dans
          le développement web.
        </p>
      </div>
    </div>
  </section>
</template>
