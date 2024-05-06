
<!--website header incl nav. to be included on every page-->
<template>
  <header class="bg-teal-100 py-4 px-8">
      <main class="container mx-auto flex flex-row justify-between items-center">
          <div class="text-black text-lg font-bold">
        <a href="/">
            <div class="flex flex-row items-center">
                <img src="/assets/logo/logoipsum-298.svg" alt="EarthSaver logo" class="h-12 w-12 py-2">
                <header>EarthSaver</header>
          </div>
        </a>
        </div>
          <nav class="flex flex-row justify-end gap-4">
              <NuxtLink to="/About">Our Story</NuxtLink>
              <NuxtLink to="/Sustainability">Sustainability</NuxtLink>
              <NuxtLink to="/Blog">Blog</NuxtLink>
              <NuxtLink to="/Contact">Contact Us</NuxtLink>
        </nav>
          <div class="items-center justify-right">
            <PrimaryButton>Download Now</PrimaryButton>
        </div>
      </main>
  </header>
</template>
