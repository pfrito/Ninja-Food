<script setup></script>

<template>
  <body class="text-gray-600 font-body">
    <div class="grid md:grid-cols-3">
      <!-- content wrapper -->
      <div class="md:col-span-1">
        <nav>
          <div>
            <h1 class="font-bold uppercase p-4 border-b border-gray-100">
              <a href="/">Food Ninja</a>
            </h1>
          </div>
          <ul>
            <li class="text-gray-700 font-bold">
              <a href="#">
                <span>Home</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span>About</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="mammoth">Contact</span>
              </a>
            </li>
          </ul>
        </nav>
      </div>
      <!-- end nav -->

      <main class="px-16 py-6 bg-gray-100 md:col-span-2">
        <div class="flex justify-center md:justify-end">
          <a href="#" class="text-primary">Login</a>
          <a href="#" class="text-primary ml-2">Sign up</a>
        </div>

        <header>
          <h2 class="text-gray-700 text-6xl font-semibold">Recipes</h2>
          <h3 class="text-2xl font-semibold">For Ninjas</h3>
        </header>

        <div>
          <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">
            Latest Recipes
          </h4>
          <div class="mt-8 grid lg:grid-cols-3 gap-10">
            <!-- cards go here -->
            <div class="card">
              <img src="./assets/stew.jpg" alt="stew" class="w-full h-32 sm:h-48 object-cover"/>
              <div class="m-4">
                <span class="font-bold ">5 Bean Chilli Stew</span>
                <span class="block text-gray-500 text-sm">Recipe by Mario</span>
              </div>
              <div class="batch">
                <span>25 mins</span>
              </div>
            </div>

            <div class="card">
              <img src="./assets/noodles.jpg" alt="noodles" class="w-full h-32 sm:h-48 object-cover"/>
              <div class="m-4">
                <span class="font-bold ">Veg Noodles</span>
                <span class="block text-gray-500 text-sm">Recipe by Mario</span>
              </div>
              <div class="batch">
                <span>25 mins</span>
              </div>
            </div>

            <div class="card">
              <img src="./assets/curry.jpg" alt="curry" class="w-full h-32 sm:h-48 object-cover"/>
              <div class="m-4">
                <span class="font-bold ">Tofu Curry</span>
                <span class="block text-gray-500 text-sm">Recipe by Mario</span>
              </div>
              <div class="batch">
                <span>25 mins</span>
              </div>
            </div>
          </div>

          <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">
            Most Popular
          </h4>
          <div class="mt-8">
            <!-- cards go here -->
          </div>

          <div class="flex justify-center">
            <div class="bg-secondary-100 text-secondary-200">Load more</div>
          </div>
        </div>
      </main>
    </div>
  </body>
</template>

<style scoped></style>
