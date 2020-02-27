<template>
        <div class="c">

        <section  class="">


          <transition name="slide-fade">

          </transition>


          <b-row  align-h="center" >

            <b-col cols="12" md="3" class="justify-content-center">
              <div class="card" >
                <img src="@/assets/img/mia2.png" class="card-img-top" alt="image profile">
                <div class="card-body">
                    <h6 class="card-title ">Javiera Torres</h6>
                    <p  class="card-title-p">Santiago, Chile</p>
                    <p class="card-text border" v-for="tag in tags">
                    {{tag}}
                      </p>
                      <a href="https://www.linkedin.com/in/javiera-torres" class="btn btn-info">Linkedin</a>
                </div>
            </div>
            </b-col>


            <b-col cols="12" md="8" class="justify-content-center">

                <div class="">
                  <h2>Projects</h2>

                  <div class="card mb-3 bg-dark ml-5" style="max-width: 800px; ">
                    <div class="row">
                      <div class="col-md-12">
                        <div class="card-body card-img-top-p ">
                          <h6 class="card-title-pp w-70 ">  Ciudad Sur </h6>
                          <div class="w-70">
                            <p  class="card-title-p">Santiago, Chile</p>
                            <p class="">Creación del concepto para proyecto fondef de vida saludable, desarrollo y diseño del sitio web responsivo del mismo.</p>
                            <p class="">Creación del concepto para proyecto fondef de vida saludable, desarrollo y diseño del sitio web responsivo del mismo.</p>
                          </div>
                        </div>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                      </div>

                    </div>
                  </div>

                  <div class="card mb-3 bg-dark ml-5" style="max-width: 800px; ">
                    <div class="row">
                      <div class="col-md-12">
                        <div class="card-body card-img-top-p ">
                          <h6 class="card-title-pp w-70 ">  Ciudad Sur </h6>                            <transition name="slide-fade">


                          <div class="w-70"v-if="show">
                            <p  class="card-title-p">Santiago, Chile</p>
                              <p >
                              <p class="">Creación del concepto para proyecto fondef de vida saludable, desarrollo y diseño del sitio web responsivo del mismo.</p>
                              <p class="">Creación del concepto para proyecto fondef de vida saludable, desarrollo y diseño del sitio web responsivo del mismo.</p></p>

                                                      <p class="">Creación del concepto para proyecto fondef de vida saludable, desarrollo y diseño del sitio web responsivo del mismo.</p>

                          </div>                            </transition>

                          <button @click="show = !show">
 Mostrar/Ocultar
</button>
                        </div>
  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                      </div>

                    </div>
                  </div>
              </div>

            </b-col>



    </b-row>
  </section>

  </div>
</template>


<script>

export default {
  el: 'projects',

  components: {
  },
  data() {
    return {
      show: true,
      tags: ["Front-end", "Vuejs", "Nuxtjs", "Project", "Design", "UX", "UI", "Developer", "Web Design", ""],
    };
  },
};
</script>
