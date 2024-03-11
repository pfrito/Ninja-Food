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
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  strokeWidth="{1.5}"
                  stroke="currentColor"
                  class="w-5"
                >
                  <path
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    d="m2.25 12 8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25"
                  />
                </svg>
              </a>
            </li>
            <li>
              <a href="#">
                <span>About</span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  strokeWidth="{1.5}"
                  stroke="currentColor"
                  class="w-5"
                >
                  <path
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    d="M9.879 7.519c1.171-1.025 3.071-1.025 4.242 0 1.172 1.025 1.172 2.687 0 3.712-.203.179-.43.326-.67.442-.745.361-1.45.999-1.45 1.827v.75M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-9 5.25h.008v.008H12v-.008Z"
                  />
                </svg>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="mammoth">Contact</span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  strokeWidth="{1.5}"
                  stroke="currentColor"
                  class="w-5"
                >
                  <path
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"
                  />
                </svg>
              </a>
            </li>
          </ul>
        </nav>
      </div>
      <!-- end nav -->

      <main class="px-16 py-6 bg-gray-100 md:col-span-2">
        <div class="flex justify-center md:justify-end">
          <a href="#" class="text-primary btn border-primary md:border-2"
            >Login</a
          >
          <a href="#" class="text-primary ml-2 btn border-primary md:border-2"
            >Sign up</a
          >
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
              <img
                src="./assets/stew.jpg"
                alt="stew"
                class="w-full h-32 sm:h-48 object-cover"
              />
              <div class="m-4">
                <span class="font-bold">5 Bean Chilli Stew</span>
                <span class="block text-gray-500 text-sm">Recipe by Mario</span>
              </div>
              <div class="batch">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  strokeWidth="{1.5}"
                  stroke="currentColor"
                  class="w-5 inline-block"
                >
                  <path
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
                  />
                </svg>
                <span>25 mins</span>
              </div>
            </div>

            <div class="card">
              <img
                src="./assets/noodles.jpg"
                alt="noodles"
                class="w-full h-32 sm:h-48 object-cover"
              />
              <div class="m-4">
                <span class="font-bold">Veg Noodles</span>
                <span class="block text-gray-500 text-sm">Recipe by Mario</span>
              </div>
              <div class="batch">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  strokeWidth="{1.5}"
                  stroke="currentColor"
                  class="w-5 inline-block"
                >
                  <path
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
                  />
                </svg>
                <span>25 mins</span>
              </div>
            </div>

            <div class="card">
              <img
                src="./assets/curry.jpg"
                alt="curry"
                class="w-full h-32 sm:h-48 object-cover"
              />
              <div class="m-4">
                <span class="font-bold">Tofu Curry</span>
                <span class="block text-gray-500 text-sm">Recipe by Mario</span>
              </div>
              <div class="batch">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  strokeWidth="{1.5}"
                  stroke="currentColor"
                  class="w-5 inline-block"
                >
                  <path
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
                  />
                </svg>
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
            <div class="bg-secondary-100 text-secondary-200 btn">Load more</div>
          </div>
        </div>
      </main>
    </div>
  </body>
</template>

<style scoped></style>
