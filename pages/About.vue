<template>
  <title>Our Story | EarthSaver</title>
  <Header/>
  <div class="relative isolate overflow-hidden bg-gray-800 py-24 sm:py-32">
    <img src="/assets/images/AdobeStock_278765257.jpeg" alt="Sustainability Superhero" class="absolute inset-0 -z-10 h-full w-full object-cover object-right md:object-center mix-blend-overlay" />
    <div class="hidden sm:absolute sm:-top-10 sm:right-1/2 sm:-z-10 sm:mr-10 sm:block sm:transform-gpu sm:blur-3xl" aria-hidden="true"></div>
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Our Story</h2>
        <p class="mt-6 text-lg leading-8 text-gray-100">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </div>
      <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
        <dl class="mt-16 grid grid-cols-1 gap-8 sm:mt-20 sm:grid-cols-2 lg:grid-cols-4">
          <div v-for="stat in stats" :key="stat.name" class="flex flex-col-reverse">
            <dt class="text-base leading-7 text-gray-300">{{ stat.name }}</dt>
            <dd class="text-2xl font-bold leading-9 tracking-tight text-white">{{ stat.value }}</dd>
          </div>
        </dl>
      </div>
    </div>
  </div>
</template>

<script setup>
const stats = [
  { name: 'Trees Planted', value: '500+' },
  { name: 'Downloads of EarthSaver', value: 'Over 200,000' },
  { name: 'Ways to Earn Rewards', value: '100+' },
]
</script>

<script>

</script>