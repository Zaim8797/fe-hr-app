<template>
    <header class="py-4 bg-white">
   <nav class="bg-blue-100 flex container items-center shadow-lg rounded-lg pt-4 pb-6 mr-1">
     <!-- Logo -->
     <NuxtLink to="/" class="flex gap-1 items-center">
       <NuxtImg width="56px" src="/icon-green.png" format="webp" alt="" />
       <span class="text-3xl font-bold text-blue-400">HR</span><span class="text-3xl font-bold">.app</span>
     </NuxtLink>

     <!-- Navigation Links -->
     <ul class="flex gap-6 ml-auto text-xl font-bold capitalize items-center">
       <li>
         <NuxtLink to="/" class="flex gap-2 items-center">
           <UIcon name="line-md:home-twotone" width="24" height="24"/>
           <span>Home</span>
         </NuxtLink>
       </li>
       <li>
         <NuxtLink to="/login" class="flex gap-2 items-center">
           <UIcon name="line-md:alert-circle-twotone-loop" width="24" height="24"/>
           <span>Login</span>
         </NuxtLink>
       </li>
       <li></li>
     </ul>
   </nav>
 </header>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>