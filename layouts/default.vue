<template>
  <div class="container flex-col justify-start mx-auto">
    <Header />
    <div class="w-full overflow-x-hidden bg-gray-100">
      <div class="p-4">
        <div class="flex justify-between mx-auto">
          <Nuxt />
          <Right />
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>
