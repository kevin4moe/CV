<script setup>
let counter = ref(0);

setInterval(() => {
  counter.value++;
}, 1000);
</script>

<template>
  <div>
    <header class="bg-white shadow">
      <div class="mx-auto max-w-7xl bg-black px-4 py-10 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-bold leading-tight text-gray-300" title="Name">
          Kevin Ulises Covarrubias Pavon
        </h1>
      </div>
    </header>
    <main>
      <router-view />
    </main>
  </div>
</template>
