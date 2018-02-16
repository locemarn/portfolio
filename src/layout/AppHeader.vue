<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark  fixed-top" id="nbar">
      <h4 style="color: dark;">Marcelo Nogueira</h4>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation" id="btn-navbar">
        <span class="navbar-toggler-icon btn btn-outline-dark"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav nav nav-pills" id="menu-list">
          <li class="nav-item">
              <a class="nav-link" href="#sobre"><button type="button" class="btn btn-outline-dark">Sobre</button></a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#projetos"><button type="button" class="btn btn-outline-dark">Projetos</button></a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#contato"><button type="button" class="btn btn-outline-dark">Contato</button></a>
          </li>
        </ul>
      </div>
    </nav>
  </div>

</template>

<script>
export default {

}
</script>

<style>
/* header */
#nbar {
  background: rgba(255,255,255,0.5);
  box-shadow: 0 0 5px;
}
#navbar {
  max-width: 100%;
}
#logo {
  width: 150px;
  height: 50px;
  margin-left: 30px;
}

#navbarNav {
  margin-right: 2%
}

</style>
