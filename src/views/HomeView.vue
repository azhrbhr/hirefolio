<template>
  <div class="bg-gray-100 min-h-screen">
    <!-- Navigation Bar -->
    <nav class="bg-white shadow-lg">
      <div class="container mx-auto py-4 px-8 flex justify-between items-center">
        <div class="flex items-center">
          <!-- Logo -->
          <img src="@\assets\logo.png" alt="Hirefolio" class="h-12 w-auto">
        </div>
        <div class="hidden md:block">
          <!-- Navigation Links -->
          <RouterLink to="/" class="text-gray-700 hover:text-gray-900 px-4">Home</RouterLink>
          <RouterLink to="/resume" class="text-gray-700 hover:text-gray-900 px-4">Resume</RouterLink>
          <a href="#" class="text-gray-700 hover:text-gray-900 px-4">Features</a>
          <a href="#" class="text-gray-700 hover:text-gray-900 px-4">About</a>
          <a href="#" class="text-gray-700 hover:text-gray-900 px-4">Contact</a>
        </div>
        <div class="md:hidden">
          <!-- Mobile Menu Icon -->
          <!-- Add your mobile menu icon here -->
        </div>
      </div>
    </nav>

    <!-- Main Section - Hero -->
    <header class="py-20 bg-gradient-to-r from-indigo-600 to-purple-700 text-white">
      <div class="container mx-auto text-center">
        <img src="@\assets\logo.png" alt="Hirefolio" class="h-20 w-auto mx-auto">
        <h1 class="text-4xl md:text-6xl font-bold mt-6">Create Your Stunning Portfolio Effortlessly</h1>
        <p class="text-lg mt-4">Showcase your skills, experiences, and projects with Hirefolio. Impress your future
          employers!</p>
        <div class="mt-8">
          <a href="#"
            class="bg-white text-indigo-600 font-semibold px-6 py-3 rounded-full hover:bg-indigo-600 hover:text-white">Get
            Started</a>
        </div>
      </div>
    </header>

    <!-- Features Section -->
    <section class="py-16">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl md:text-4xl font-bold mb-8">Features</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Feature Cards - You can add more -->
          <div class="bg-white rounded-lg shadow-md p-6">
            <h3 class="text-xl font-semibold mb-3">Easy to Use</h3>
            <p class="text-gray-700">Create your portfolio/resume effortlessly with our user-friendly interface.</p>
          </div>
          <div class="bg-white rounded-lg shadow-md p-6">
            <h3 class="text-xl font-semibold mb-3">Customizable</h3>
            <p class="text-gray-700">Tailor your portfolio to your style with customizable templates.</p>
          </div>
          <div class="bg-white rounded-lg shadow-md p-6">
            <h3 class="text-xl font-semibold mb-3">Shareable</h3>
            <p class="text-gray-700">Share your portfolio with a simple link to anyone, anytime.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-900 text-white py-8">
      <div class="container mx-auto text-center">
        <p>&copy; 2024 Hirefolio. All Rights Reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
</script>

