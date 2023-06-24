<script setup>
  let name = 'John Doe'
</script>

<template>
  <div class="container mx-auto flex">
    <div class="w-[300px] h-screen bg-slate-500 p-5 text-white">
      Logo
    </div>
    <div class="w-full h-screen bg-slate-300 p-5 text-white">
      {{ name }}
    </div>
  </div>
</template>