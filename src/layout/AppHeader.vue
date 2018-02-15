<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
      <h4 style="color: #e2e5e5">Marcelo Nogueira</h4>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation" id="btn-navbar">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav nav nav-pills" id="menu-list">
          <li class="nav-item">
              <a class="nav-link" href="#sobre"><button type="button" class="btn btn-outline-light">Sobre</button></a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#portfolio"><button type="button" class="btn btn-outline-light">Portfolio</button></a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#contato"><button type="button" class="btn btn-outline-light">Contato</button></a>
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
#navbar {
  max-width: 100%;
}
#logo {
  width: 150px;
  height: 50px;
  margin-left: 30px;
}

#navbarNav {
  margin-right: 2%;
}

#btn-close {
  color: #e2e5e5;
  font-size: 50px;
}

</style>
