<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://github.com">
      <img src="../assets/github.png" width="30" height="30">
      <a class="title is-4 margenesTitulo">Presentación</a>
    </a>

    <a role="button" class="navbar-burger " aria-label="menu" aria-expanded="false" data-target="navbarBasicExample" id="burger" @click="menuDesplegable">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item" href="#habilidades">
        Habilidades
      </a>

      <a class="navbar-item" href="#contacto">
        Contacto
      </a>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons" @click="irRepositorio">
          <a class="button is-primary" href="https://github.com/AxlGalicia?tab=repositories">
            <strong>Repositorio</strong>
          </a>
        </div>
      </div>
    </div>
  </div>
</nav>
</template>

<script setup>

function menuDesplegable(event) {
  const burgerIcon = document.querySelector('#burger');
  const navbarMenu = document.querySelector('#navbarBasicExample');
  burgerIcon.classList.toggle('is-active')
  navbarMenu.classList.toggle('is-active');
}

/*burgerIcon.addEventListener('click',() => {
    navbarMenu.classList.toggle('is-active');
});*/

</script>

<style scoped>

.margenesTitulo
{

  margin-left: 1rem;

}

</style>