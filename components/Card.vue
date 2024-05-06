<!--card component-->
<template>
  <div class="px-4 py-8">
    <h1 class="flex justify-center font-bold text-2xl">Sustainability</h1>
    <p class="flex justify-center text-lg">We always aim to practice what we preach. Read below to see how we're practicing sustainability here at headquarters.</p>
  </div>
  <div class="card-grid">
    <div class="card-style">
      <img src="/assets/images/proxyclick-visitor-management-system-s86WhGhp25Y-unsplash.jpg" class="image-style" alt="Team Photo">
      <div class="card-content">
        <h1 class="font-bold text-xl mb-2">Carbon Neutral Office</h1>
        <p class="text-gray-700 text-base">We've implemented energy-efficient lighting, smart thermostats, and power-saving technologies to reduce our energy consumption.</p>
      </div>
    </div>

    <div class="card-style">
      <img src="/assets/images/proxyclick-visitor-management-system-s86WhGhp25Y-unsplash.jpg" class="image-style" alt="Sunset">
      <div class="card-content">
        <h1 class="font-bold text-xl mb-2">Energy Efficiency</h1>
        <p class="text-gray-700 text-base">We've implemented energy-efficient lighting, smart thermostats, and power-saving technologies to reduce our energy consumption.</p>
      </div>
    </div>

    <div class="card-style">
      <img src="/assets/images/proxyclick-visitor-management-system-s86WhGhp25Y-unsplash.jpg" class="image-style" alt="Sunset">
      <div class="card-content">
        <h1 class="font-bold text-xl mb-2">Waste Reduction</h1>
        <p class="text-gray-700 text-base">Recycling and composting are integral parts of our waste management strategy. We've also minimized single-use plastics and paper usage throughout the office.</p>
      </div>
    </div>
  
    <div class="card-style">
      <img src="/assets/images/proxyclick-visitor-management-system-s86WhGhp25Y-unsplash.jpg" class="image-style" alt="Sunset">
      <div class="card-content">
        <h1 class="font-bold text-xl mb-2">Carbon Neutral Office</h1>
        <p class="text-gray-700 text-base">We've implemented energy-efficient lighting, smart thermostats, and power-saving technologies to reduce our energy consumption.</p>
    </div>
  </div>

  <div class="card-style">
      <img src="/assets/images/proxyclick-visitor-management-system-s86WhGhp25Y-unsplash.jpg" class="image-style" alt="Sunset">
      <div class="card-content">
        <h1 class="font-bold text-xl mb-2">Sustainable Sourcing</h1>
        <p class="text-gray-700 text-base">From office supplies to furniture, we prioritize products that are ethically sourced and environmentally friendly.</p>
      </div>
    </div>
  
    <div class="card-style">
      <img src="/assets/images/proxyclick-visitor-management-system-s86WhGhp25Y-unsplash.jpg" class="image-style" alt="Sunset">
      <div class="card-content">
        <h1 class="font-bold text-xl mb-2">Transportation Alternatives</h1>
        <p class="text-gray-700 text-base">Encouraging our employees to carpool, bike, or use public transportation reduces our collective carbon footprint.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card-style {
  background-color: white;
  height: 400px;
  width: 350px;
  margin: 16px 24px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  border-radius: 10px;
  color: black;
  text-align: left;  
}

.card-image {
  height: 250px;
  width: 350px;
  object-fit: cover;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

.card-content {
  padding: 15px;
  height: 100px;
  text-overflow: ellipsis;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-auto-rows: auto;
  grid-gap: 1rem;
  justify-content: center;
  align-items: center;
}
</style>