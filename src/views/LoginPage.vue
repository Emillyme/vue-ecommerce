<script setup>
import InputGeral from '@/components/inputGeral.vue';

</script>

<template>
  <main class="bg-gray-100 w-screen h-screen flex justify-center">
    <div class="flex bg-white w-screen my-10 mx-10 ">
      <div class="w-[800px]">
        <img src="/src/assets/coffeebg.jpg" class="w-full h-full object-cover">
      </div>

      <div class="w-full flex justify-center items-center flex-col">
        <div class="flex justify-center items-center flex-col mb-20">
          <h1 class="font-medium text-2xl mb-2">Welcome back</h1>
          <p class="text-gray-500">Our best coffe for your favorite coffee shop!</p>
        </div>
        <div class="">
          <form action="" class="flex flex-col">
            <InputGeral nomeLabel="Username" type="text"/>
            <InputGeral nomeLabel="Password" type="password"/>
            <button>
              Login
            </button>
          </form>
        </div>
      </div>

    </div>
  </main>
</template>
