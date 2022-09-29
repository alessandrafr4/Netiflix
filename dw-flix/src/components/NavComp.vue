<template>
  <nav class="navbar navbar-expand-lg navbar bg-dark">
    <div class="container-fluid p-3">
      <a class="navbar-brand p-1">Megaflix</a>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item p-1">
            <RouterLink to="/" class="nav-link links">Adultos</RouterLink>
          </li>
          <li class="nav-item p-1">
            <RouterLink to="/filmes" class="nav-link links">Crianças</RouterLink>
          </li>
          <li class="nav-item p-1">
            <RouterLink to="/series" class="nav-link links">Jovens/Adolescentes</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
