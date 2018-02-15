<template>
  <div>
    <footer id="footer">
      <!-- <div class="container"> -->
          <div class="row col-xs-12 col-md-12 col-sm-12">
                <!-- <small style="font-size: 10px;">v.1.0</small> -->
              <div id="rodape-social" class="col-xs-4 col-md-4 col-sm-4">
                  <div>
                      <a href="https://github.com/locemarn" class="img-fluid" target="_blank"><i class="fa fa-github" aria-hidden="true" id="social"></i></a>
                  </div>
                  <div>
                      <a href="https://twitter.com/Locemarn" class="img-fluid" target="_blank"><i class="fa fa-twitter" aria-hidden="true" id="social"></i></a>
                  </div>
                  <div>
                      <a href="https://www.linkedin.com/in/marcelo-nogueira-408920109/" class="img-fluid" target="_blank"><i class="fa fa-linkedin" aria-hidden="true" id="social"></i></a>
                  </div>
                  <div>
                      <a href="https://codepen.io/locemarn/" class="img-fluid" target="_blank"><i class="fa fa-codepen" aria-hidden="true" id="social"></i></a>
                  </div>
                  <!-- <div>
                      <a href="https://medium.com/@Locemarn" class="img-fluid" target="_blank"><i class="fa fa-medium" aria-hidden="true" id="social"></i></a>
                  </div>
                  <div>
                      <a href="https://www.freecodecamp.org/locemarn" class="img-fluid" target="_blank"><i class="fa fa-free-code-camp" aria-hidden="true" id="social"></i></a>
                  </div> -->

              </div>
              <!-- <div class="col-xs-6 col-md-6 col-sm-6" id="rodape">
                  <h5> SOBRE A PÁGINA:</h5>
                  <p>Feito por <a href="#" id="nome-rodape">Marcelo Nogueira,</a> com <i class="fa fa-html5" aria-hidden="true"></i>, <i class="fa fa-css3" aria-hidden="true"></i>, <i class="fab fa-vuejs" aria-hidden="true"></i> e <i class="fa fa-music" aria-hidden="true"></i>.</p>
              </div> -->
          </div>
      <!-- </div> -->
    </footer>
  </div>
</template>

<script>
export default {

}
</script>

<style>

#footer {
  background-color: #717878;
  width: 100%;
  height: auto;
  color: #e2e5e5;
}

#rodape {
  padding-left: 10%;
  padding-top: 14rem;
}

#rodape-social {
  padding: 0;
  font-size: 30px;
  display: flex;
  margin-left: 40%;
}

#social {
  color: #e2e5e5;
  max-width: 100%;
  height: auto;
  padding-right: 1rem;
}

#social:hover {
  color: #fff;
  font-size: 35px;
  color: #fff;
  }

  #nome-rodape {
  color: #e2e5e5;
}

#nome-rodape:hover {
  color: #fff;
  font-size: 18px;
  text-decoration: none;
}

</style>
