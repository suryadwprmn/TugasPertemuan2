<template>
  <nav class="navbar navbar-expand-lg bg-dark py-3" >
  <div class="container">
    <a class="navbar-brand fw-semibold" href="#">Indonesian<span class="text-danger text-italic">Movies</span></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav align">
        <li class="nav-item">
          <a class="nav-link text-light" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-light">List Film</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-light" href="#">DOCS API</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<style>
:root{
  --primary :#0D1282;
  --bg:#EEEDED;
}


.container .navbar-brand{
  font-size: 2rem;
  color: var(--bg);
}
.navbar .navbar-expand-lg .bg-dark .py-3 .container .navbar-toggler-icon{
  color: var(--bg);
}

</style>
