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
              <li class="nav-item"><a href="#explore-head-section" class="nav-link">Explore</a></li>
              <li class="nav-item"><a href="#create-head-section" class="nav-link">Create</a></li>
              <li class="nav-item"><a href="#share-head-section" class="nav-link">Share</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <!-- home section -->
    <section id="home-section">
      <div class="overlay overlay--dark">
        <div class="container container--pt">
          <div class="card bg-primary text-center card--low-opacity">
            <div class="card-body">
              <h3>Sign Up Today</h3>
              <p>Please fill out this form to register</p>
              <form action="post">
                <div class="form-group"><input type="text" class="form-control form-control-lg" placeholder="Username"></div>
                <div class="form-group"><input type="email" name="email" id="email" class="form-control form-control-lg" placeholder="Email"></div>
                <div class="form-group"><input type="password" name="password" id="password" class="form-control form-control-lg" placeholder="Password"></div>
                <div class="form-group"><input type="password" name="confirmPassword" id="confirmPassword" class="form-control form-control-lg" placeholder="Confirm Password"></div>
                <button class="btn btn-outline-light btn-block">Submit</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- explore head section-->
    <div id="explore-head-section">
      <div class="container">
        <div class="text-center py-5">
          <h1 class="display-4">Explore</h1>
          <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt mollitia cupiditate dolores a ducimus eos asperiores
            repudiandae sapiente ratione, error vero numquam impedit, unde excepturi pariatur quos quisquam odio odit.</p>
          <a href="#" class="btn btn-outline-secondary">Find Out More</a>
        </div>
      </div>
    </div>
    <!-- explore section -->
    <section id="explore-section" class="text-muted bg-light py-5">
      <div class="container ">
        <img src="./assets/img/explore-section1.jpg" alt="explore img" class="img-fluid mb-3 rounded-circle">
        <h3>Explore & Connect</h3>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Et officiis expedita voluptatem obcaecati facilis vero
          amet vitae labore tenetur iusto debitis cum asperiores necessitatibus consequuntur est, ratione eum esse ab!</p>
        <div class="d-flex">
          <div class="p-4">
            <i class="fa fa-check fa-check--bg-dark"></i>
          </div>
          <div class="p-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi ab molestias dignissimos atque blanditiis voluptatibus molestiae
          </div>
        </div>
        <div class="d-flex">
          <div class="p-4"><i class="fa fa-check fa-check--bg-dark"></i></div>
          <div class="p-4 ">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            Ut, cum?
          </div>
        </div>
      </div>
    </section>
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