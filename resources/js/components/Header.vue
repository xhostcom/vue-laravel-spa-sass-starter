<template>
 <!-- Navigation -->
 <nav class="navbar navbar-expand-lg navbar-dark bg-dark static-top">
  <div class="container">
   <router-link to="/" class="navbar-brand">
          <img src="../../img/Logo.png" alt="Logo">
        </router-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
    <div class="collapse navbar-collapse" id="navbarResponsive">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active">
         <router-link class="nav-link" to="/">Home
                <span class="sr-only">(current)</span>
        </router-link>
        </li>
      </ul>
	</div>
  </div>
</nav>
</template>
