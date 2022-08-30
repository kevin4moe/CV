<route lang="json">
{
  "meta": {
    "title": "Home"
  }
}
</route>

<script setup>
useHead({
  title: "Home",
});
</script>

<template>
  <div class="flex flex-row flex-wrap bg-gray-50">
    <aside id="resume" class="w-full bg-black py-12 text-white md:w-1/3">
      <section id="aboutme" class="mx-2">
        <header>
          <h2 class="text-lg font-semibold">SOBRE MI</h2>
        </header>
        <div class="ml-2">
          <p class="text-sm font-semibold">
            Estudiante de Licenciatura en Economía.
          </p>
          <p class="text-sm">
            Me considero una persona responsable, ordenada y con ganas de seguir
            aprendiendo.
          </p>
          <p class="text-sm">
            Cuento con experiencia en creación de paginas web y proyectos de
            analisis en R.
          </p>
        </div>
      </section>
      <section id="grade" class="mx-2">
        <header>
          <h2 class="text-lg font-semibold">Formación Academica</h2>
        </header>
        <div class="ml-2">
          <ul>
            <li>
              <p class="text-sm">Licenciatura en Economía</p>
              <p class="text-xs italic">
                Universidad de Guanajuato (Actualmente cursando)
              </p>
            </li>
          </ul>
        </div>
      </section>
      <section id="contact" class="mx-2">
        <header>
          <h2 class="text-lg font-semibold">Contacto</h2>
        </header>
        <ul>
          <li title="email" class="align-center flex flex-row text-sm">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="h-6 w-6 pb-1"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"
              />
            </svg>
            <span class="">kevin4moe@gmail.com</span>
          </li>
          <li title="phone" class="align-center flex flex-row text-sm">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="h-6 w-6 pb-1"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"
              />
            </svg>
            <span>473-164-9222</span>
          </li>
        </ul>
      </section>
    </aside>
    <main class="w-full py-12 md:w-2/3">
      <header class="ml-2">
        <h2 class="text-3xl font-light">Proyectos</h2>
      </header>
      <div class="mx-2">
        <ul class="grid grid-cols-1 gap-1 md:grid-cols-2 lg:grid-cols-3">
          <li class="m-1 flex flex-col justify-evenly rounded-lg p-2 shadow">
            <header class="mb-1">
              <a
                href="https://placer-espresso.netlify.app/"
                target="_blank"
                rel="noopener noreferrer"
              >
                <h3 class="text-lg font-semibold underline">
                  Menú: Placer Espresso
                </h3>
              </a>
              <p class="text-sm italic">
                Sitio web para la cafeteria Placer Espresso
              </p>
            </header>
            <p class="px-2 text-sm">
              La pagina fue hecha para contener la información de contacto, el
              menú que manejan, ademas de enlaces utiles de sus redes sociales.
            </p>
            <div
              class="mt-auto h-40 w-full touch-auto overflow-y-auto rounded shadow"
            >
              <img
                class="w-full"
                src="../assets/img/2.png"
                alt="Pagina de Placer Espresso"
              />
            </div>
          </li>
          <li class="m-1 flex flex-col justify-evenly rounded-lg p-2 shadow">
            <header class="mb-1">
              <a
                href="https://mendez-remodeling-atl-llc.netlify.app/"
                target="_blank"
                rel="noopener noreferrer"
              >
                <h3 class="text-lg font-semibold underline">
                  Remodeladora: Mendez Remodeling ATL LLC
                </h3>
              </a>
              <p class="text-sm italic">
                Sitio web para la remodeladora Mendez Remodeling ATL LLC
              </p>
            </header>
            <p class="px-2 text-sm">
              La pagina fue hecha para contener la información de contacto, los
              servicios que manejan, ademas de enlaces utiles de sus redes
              sociales.
            </p>
            <div
              class="mt-auto h-40 w-full touch-auto overflow-y-auto rounded shadow"
            >
              <img
                src="../assets/img/1.png"
                alt="Pagina de Mendez Remodeling ATL LLC"
              />
            </div>
          </li>
          <li class="m-1 flex flex-col justify-evenly rounded-lg p-2 shadow">
            <header class="mb-1">
              <a
                href="https://github.com/kevin4moe/K-Nearest-Neighbor-KNN-"
                target="_blank"
                rel="noopener noreferrer"
              >
                <h3 class="text-lg font-semibold underline">
                  K-Nearest Neighbor (KNN)
                </h3>
              </a>
              <p class="text-sm italic">
                Proyecto en R, crear nuestro propia versión del l algoritmo KNN
              </p>
            </header>
            <p class="px-2 text-sm">
              El KNN es la técnica de clasificación más fundamental y simple
              cuando hay muy poco o nulo conocimiento sobre la distribución de
              los datos.
            </p>
            <div class="mt-auto w-full touch-auto rounded shadow">
              <img src="../assets/img/3.png" alt="K-Nearest-Neighbor-KNN" />
            </div>
          </li>
        </ul>
      </div>
    </main>
    <footer
      class="flex h-40 w-full flex-col justify-center bg-gray-900 text-white"
    >
      <div class="">
        <p class="text-center text-sm font-light">Currículum Vitae</p>
      </div>
    </footer>
  </div>
</template>
