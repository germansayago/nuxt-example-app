<template>
  <div>    
    <div class="d-flex justify-content-between align-item-center">
      <h1 class="py-4 mb-3">
        <nuxt-link to="/" class="text-dark text-decoration-none font-weight-bold">My Aplication</nuxt-link>
      </h1>
      <div class="d-flex mt-4">
        <div class="p-3"><nuxt-link to="/about" class="text-dark">About</nuxt-link></div>
        <div class="p-3"><nuxt-link to="/team" class="text-dark">Team</nuxt-link></div>
      </div>
    </div>

    <div class="border border-bottom border-gray mb-5"></div>
  </div>
</template>

<style>
  .nuxt-link-active{
    text-decoration: underline;
    font-weight: bold;
  }
</style>
