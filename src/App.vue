<template>
  <div>
    <!-- main header -->
    <header>
      <nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top">
        <div class="container">
          <a href="index.html" class="navbar-brand navbar-brand--white">BS1</a>
          <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
                  <span class="navbar-toggler-icon"></span>
                </button>
          <div class="collapse navbar-collapse" id="navbarCollapse">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a href="#home-section" class="nav-link">Home</a>
              </li>
              <li class="nav-item"><a href="#explore-section" class="nav-link">Explore</a></li>
              <li class="nav-item"><a href="#create-section" class="nav-link">Create</a></li>
              <li class="nav-item"><a href="#share-section" class="nav-link">Share</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
  </div>

</template>
<script>
  const $ = require("jquery")
  window.jQuery = $;
  require("bootstrap")

</script>
<style>
  @import "bootstrap";
  @import "./assets/css/main.css";
</style>