<template>
   <nav>
       <div class="nav-wrapper green">
           <div class="container">
               <router-link :to="{name: 'Dashboard'}" class="brand-logo">Employee Manager</router-link>
           </div>
       </div>
   </nav>
</template>

<style>
@media only screen and (max-width: 600px) {
  nav .brand-logo {
    font-size: 20px !important;
  }
}
</style>
