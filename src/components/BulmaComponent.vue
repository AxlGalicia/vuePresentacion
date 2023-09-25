<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://github.com">
      <img src="../assets/github.png" width="30" height="30">
      <a class="title is-4 margenesTitulo">Presentacion</a>
    </a>

    <a role="button" class="navbar-burger " aria-label="menu" aria-expanded="false" data-target="navbarBasicExample" id="burger" @click="menuDesplegable">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">
        Quien Soy
      </a>

      <a class="navbar-item">
        Skills
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Mas
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            Experiencia
          </a>
          <a class="navbar-item">
            Contacto
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary">
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