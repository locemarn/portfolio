<template>
  <div>
    <div class="" id="corpo" style="width: 100%;">
      <!-- sobre -->
      <div data-spy="scroll" data-target="#navbar-example2" data-offset="0">

        <div class="row">
            <div id="sobre" class="media col-xs-12 col-md-12 col-sm-12">
                <div class="col-xs-6 col-md-8 col-sm-6" id="descricao">
                    <p>Estudante do 8º semestre de Engenharia da Computação, em busca da primeira oportunidade na área de Tecnologia da Informação. Além da universidade, estudo por conta, JavaScript, VueJS e Laravel com PHP.</p>
                    <p>Estudando para ser um fullstack developer, já possuindo conhecimentos básicos em PHP, JavaScript, NodeJS, VueJS, MySql, Mongodb, Firebase e Git.</p>
                    <div  id="linha-header">
                    </div>
                    Além disso gosto de me manter em movimento, sempre praticando alguma atividade física, como Jiu-Jitsu, corrida, natação ou qualquer outro esporte que faça o corpo e mente trabalharem juntos! :)
                </div>
                <div class="align-self-center col-xs-4 col-md-4 col-sm-4">
                    <img src="../assets/me.jpg" alt="Eu" id="image-eu">
                </div>
            </div>
        </div>

        <!-- PROJETOS -->
        <div class="row" id="projetos" >
          <div class="col-xs-12 col-md-12 col-sm-10">
            <div>
                <h4 class="text-center">PROJETOS</h4>
            </div>

            <div class="col-md-10 offset-md-1 col-sm-8 offset-sm-2">
              <!-- CICLO DE PROJETOS -->
              <div class="media" style="margin-top:5%;" id="port">
                  <img class="align-self-center mr-3" data-toggle="modal" data-target="bd-example-modal-lg" src="../assets/ecommerce01.png" id="img-port" alt="ecommerce imagem">
                  <div class="media-body">
                      <h5 class="mt-0">E- commerce</h5>
                      <p>E-commerce feito para um projeto da faculdade, onde penso em dar continuidade. Feito em PHP, Slim Framework e MySql, em acompanha-
                          mento do curso da <a href="https://www.udemy.com/curso-php-7-online/learn/v4/" target="_blank">HCode</a> na plataforma <a href="https://www.udemy.com">Udemy</a>, onde apresentei como projeto final da matéria.</p>
                      <p class="mb-0">Acesso ao repositório: <a href="https://github.com/locemarn/ecommerce" target="_blank"><i class="fa fa-github" aria-hidden="true" id="social-l"></i> GitHub</a>.</p>
                  </div>
              </div>

              <div class="media"  style="margin-top:5%;" id="port">
                  <div class="media-body">
                      <h5 class="mt-0 mb-1">Monster Slayer</h5>
                      <p>"Game" feito como exercício do curso <a href="https://www.udemy.com/vuejs-2-the-complete-guide/learn/v4/overview" target="_blank">Vue JS 2 - The Complete Guide</a>, da plataforma <a href="https://www.udemy.com" target="_blank">Udemy.</a></p>
                      <p>Curso de aprendizado da Biblioteca <a href="https://vuejs.org/" target="_blank">VueJS</a>. <a href="https://github.com/locemarn/MonsterSlayerGame" target="_blank"><i class="fa fa-github" aria-hidden="true" id="social-l"></i> GitHub</a>.</p>
                  </div>
                  <img class="ml-3" src="../assets/monster.png" alt="Monster Slayer Game" id="img-port">
              </div>

              <div class="media" style="margin-top:5%;" id="port">
                  <img class="align-self-center mr-3" src="../assets/blogLaravel.png" id="img-port" alt="Laravel Blog">
                  <div class="media-body">
                      <h5 class="mt-0">Blog com Laravel</h5>
                      <p>Blog feito acompanhado da série <a href="https://www.youtube.com/watch?v=rzxNpfiLHSg&list=PLwAKR305CRO_cukAejlt5kz3pTtDMW_Cd" target="_blank">DevMarketer</a>, com as tecnologias: Laravel e VueJS. Foi realizado a parte administrativa do blog, para acrescentar as notícias e ainda não terminado.</p>
                      <p class="mb-0">Em breve adicionarei no GitHub para quem quiser acompanhar ou colaborar!</p>
                  </div>
              </div>

              <div class="media"  style="margin-top:5%;" id="port">
                  <div class="media-body">
                      <h5 class="mt-0 mb-1">Dev Meetup</h5>
                      <p>Blog realizado em acompanhamento da série <a href="https://www.youtube.com/watch?v=FXY1UyQfSFw&list=PL55RiY5tL51qxUbODJG9cgrsVd7ZHbPrt" target="_blank">Academind</a>, com as tecnologias: VueJS, Vuetify e FireBase. O acompanhamento da série foi feito para aprendizado básico das tecnologias citadas.</p>
                      <p class="mb-0">Projeto no Bitbucket em particular, porém em breve no GitHub para acesso pΰublico.</p>
                  </div>
                  <img class="ml-3" src="../assets/DevMeetup.png" alt="Dev Meetup Blog" id="img-port">
              </div>

            </div>
          </div>
        </div>

        <div class="row"  id="contato" >
          <div class="col-12">
            <h4 id="contato-text">CONTATO</h4>
          </div>
          <div class="col-1"></div>
          <div class="col-5 text-center">
            <form>
              <div class="form-group">
                  <input type="text" class="form-control" id="nome" placeholder="Nome: " v-model="contato.nome">
              </div>
              <div class="form-group">
                  <input type="email" class="form-control" id="formGroupExampleInput2" placeholder="E-mail:" v-model="contato.email">
              </div>
              <div class="form-group">
                  <input type="tel" class="form-control" id="formGroupExampleInput2" placeholder="Telefone:" v-model="contato.telefone">
              </div>
              <div class="form-group">
                  <textarea name="mensagem" id="mensagem" cols="56" rows="7" placeholder=" Mensagem: "  style="width: 100%;" v-model="contato.mensagem"></textarea>
              </div>
              <div class="form-group">
                  <button type="button" class="btn btn-outline-dark" @click="submit">Enviar</button>
              </div>

              <div class="alert alert-success alert-dismissible fade show" role="alert" v-show="ok">
                Mensagem enviada com sucesso!
                <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                  <span aria-hidden="true">&times;</span>
                </button>
              </div>
              <div class="alert alert-danger alert-dismissible fade show" role="alert" v-show="notok">
                Por favor, preencha todos os campos. Obrigado!
                <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                  <span aria-hidden="true">&times;</span>
                </button>
              </div>

              <br>
            </form>
          </div>
          <!-- <div class="col-1"></div> -->
          <div class="col-5" id="descricao-contato">
            <p>Olá, tudo bem??</p>
            <p>Quer entrar em contato comigo?? Seja para solicitar mais informações sobre minha pessoa, minha experiência, conversar ou filosofar sobre a vida. Sinta-se livre para deixar mensagem a qualquer momento.</p>
            <p>Prometo responder!</p>
            <p>Você pode também pegar meu currículo no botão abaixo.</p>

            <a href="https://drive.google.com/file/d/1tNcCZ0eZ6oHFTRBsgMT-GfC8Y88gqMRZ/view?usp=sharing"  target="_blank" class="btn btn-outline-dark  " role="button" aria-pressed="true" style="margin-bottom: 10px">Currículo</a>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Vue from 'vue'
import VueResource from 'vue-resource'

Vue.use(VueResource)

export default {
  data () {
    return {
      contato: {
        nome: '',
        email: '',
        telefone: '',
        mensagem: '',
        data: Date()
      },
      ok: false,
      notok: false
    }
  },
  methods: {
    submit () {
      if (this.contato.nome !== '' && this.contato.email !== '' && this.contato.telefone !== '' && this.contato.mensagem !== '') {
        this.$http.post('https://form-bc7e3.firebaseio.com/data.json', this.contato).then(response => {
          this.contato.nome = ''
          this.contato.email = ''
          this.contato.telefone = ''
          this.contato.mensagem = ''
          this.ok = true
        }, error => {
          console.error(error)
          this.notok = true
        })
      } else {
        this.notok = true
      }
    }
  }
}
</script>

<style>
/* sobre */
#corpo {
  color: #717878;
  margin-top: 5.2%;
  width: 100%;
  /* background: #eeeeee; */
}

#sobre {
  width: auto;
  height: auto;
  /* box-shadow: 1px 1px 20px #606868; */
  background: #e6ffde;
  padding-top: 3%;
  padding-bottom: 7%;
  margin-bottom: 5%;
}

#descricao {
  padding-left: 10%;
  padding-top: 5rem;
  padding-bottom: 5rem;
  padding-right: 5%;
}

#linha-header {
  height: 3px;
  background-color: #fff;
  border-radius: 20%;
  margin-left: 10%;
  margin-bottom: 5%;
  margin-top: 5%;
  margin-right: 15%;
}

  /* border: 3px solid #e2e5e5; */
#image-eu {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  box-shadow: 1px 1px 20px #606868;
  margin-left: 7%;
}

/* projetos */

#port {
  padding: 5%;
  box-shadow: 1px 1px 20px #e6ffde;
  padding-bottom: 8%;
  margin-bottom: 1%;
}

#img-port {
  max-width: 40%;
  height: 200px;
}

/* CONTATO */

#contato {
  padding-top: 8%;
  /* box-shadow: 1px 1px 20px #606868; */
}

#contato-text {
  text-align: center;
  margin-bottom: 8rem;
}

#descricao-contato {
  text-align: center;
}

</style>
