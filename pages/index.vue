<template>
  <div>
    <section class="bg-neutral-900 min-h-screen text-white flex items-center px-10 relative">

      <!-- Navbar -->
      <div class="absolute top-0 left-0 right-0 font-serif flex items-center justify-center py-2 text-4xl">Zack Plauché</div>

      <!-- Main Content -->
      <div class="mx-auto w-full max-w-screen-2xl grid grid-cols-10">
        
        <!-- Text and CTA -->
        <div class="col-span-5 flex items-center">
          <div>
            <h1 class="font-bold text-7xl">Group Courses</h1>
            <p class="text-2xl mt-4">Learn to code from a seasoned developer AND code mentor <b class="bg-clip-text text-transparent bg-gradient-to-r from-blue-300 to-blue-300">that knows how to teach!</b></p>
            <p class="mt-3 text-lg">The same great training, 1/10th the price.</p>
            <div class="font-bold text-5xl mt-5 leading-tight"><span class="line-through text-6xl text-red-500">$250 for 1 lesson</span><br>
              <span class="text-green-500">$600 for 24 lessons ($25/lesson)</span></div>
            <a href="" class="button text-2xl mt-10 px-10 py-5 transition-colors duration-200 ease-[ease] hover:bg-blue-400">Enroll Now</a>
          </div>
        </div>

        <!-- Image -->
        <div class="aspect-square rounded-full overflow-hidden col-span-5 w-5/6 place-self-end">
          <img 
            src="/images/zack/moldova-pro-photo-rectangle.jpg" 
            alt="Zack Plauché looking professional and cool staring at you." 
            class="object-[-40px] object-cover w-full h-full" />
        </div>

      </div>

  <!-- Logo Marquee-->
  <!-- <div class="absolute bottom-0 right-0 left-0 flex gap-5">
    <div v-for="icon in icons" class="aspect-square h-24" >
      <img :src="icon.url" :alt="icon.name + 'Logo'" class="object-contain object-center h-full w-full">
    </div>
  </div> -->
</section>
</div>
</template>

<script setup lang="ts">
import { icons } from '~/icons'

const subject = ref('Python')

</script>