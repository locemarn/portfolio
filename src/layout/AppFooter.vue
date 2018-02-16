<template>
  <div>
    <footer id="footer">
      <!-- <div class="container"> -->
          <div class="row col-xs-12 col-md-12 col-sm-12">
            <div class="col-5">
            </div>
              <div id="rodape-social" class="col-xs-4 col-md-4 col-sm-4 text-center">
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
  background-color: #030303;
  height: auto;
  color: #e2e5e5;
}

#rodape-social {
  padding: 0;
  font-size: 30px;
  display: inline-flex;
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

</style>
