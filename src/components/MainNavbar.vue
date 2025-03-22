<template>
<section class="main-navbar">
    <div class="container">
        <nav class="navbar navbar-expand-lg">
      <!-- Logo -->
      <a class="navbar-brand" href="#">
        <div class="logo-wrapper">
        <img src="../assets/logo.png" alt="Logo">
    </div>
      </a>

      <!-- Toggle Button for Mobile View -->
      <button 
        class="navbar-toggler" 
        type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false" 
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Navbar Links -->
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Work</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
   
  </nav>
    </div>

</section>
</template>
<script>
export default {
    name: 'MainNavbar'
}
</script>
