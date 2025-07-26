<template>
    <div class="flex min-h-screen bg-gray-100">

       <sidebar class="w-64 bg-white shadow-md p-4">
      <h2 class="text-2xl font-bold mb-6">My App</h2>
      <nav class="space-y-2">
        <router-link to="/" class="block px-4 py-2 rounded hover:bg-blue-600 text-gray-700" active-class="bg-blue-200 font-semibold">
          Home
        </router-link>
        <router-link to="/about" class="block px-4 py-2 rounded hover:bg-blue-100 text-gray-700" active-class="bg-blue-200 font-semibold">
          About
        </router-link>
      </nav>
    </sidebar>
  </div>

  <router-view/>
</template>
