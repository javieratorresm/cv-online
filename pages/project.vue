
<template>
        <div class="c">

        <section  class="">
          <b-row  align-h="center" >

          <!--  <b-col cols="12" md="3" class="justify-content-center">
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
          </b-col>-->

            <b-col cols="12" md="8" class="justify-content-center">
                <div class="">
                  <h2>Projects</h2>
                  <div id="main" data-anijs="if:mouseover, do: bounce animated, to: .learn">

                  <div class="card mb-3 bg-dark ml-5" style="max-width: 800px; ">
                    <div class="row">
                      <div
                          data-aos="fade-up"
                          data-aos-offset="200"
                          data-aos-delay="50"
                          data-aos-duration="1000"
                          data-aos-easing="ease-in-out"
                          data-aos-mirror="true"
                          data-aos-once="false"
                          data-aos-anchor-placement="top-center"
                        >
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
                  </div>
                </div>

              </div>

            </b-col>
            <b-col cols="12" md="8" class=" learn justify-content-center">
                <div class="">
                  <h2>Projects</h2>

                  <div class="card mb-3 bg-dark ml-5" style="max-width: 800px; ">
                    <div class="row">
                      <div
                          data-aos="fade-up"
                          data-aos-offset="200"
                          data-aos-delay="50"
                          data-aos-duration="1000"
                          data-aos-easing="ease-in-out"
                          data-aos-mirror="true"
                          data-aos-once="false"
                          data-aos-anchor-placement="top-center"
                        >
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
                  </div>

              </div>

            </b-col>


    </b-row>
  </section>

  </div>
</template>


<script>

export default {
  data() {
    return {
      show: true,
      tags: ["Front-end", "Vuejs", "Nuxtjs", "Project", "Design", "UX", "UI", "Developer", "Web Design", ""],
      description_1: "I participated in the development of the Healthy living south city Fondef project, I created the concept to be developed on the website, developing it using vuejs, nutxjs, and UX/UI user experience concepts. In addition, I  established the guidelines of the project's social media plan, advising on the creation, content, and other matters related to the design. I am currently the PMO of the technology area, in charge of the team and the 3 software modules in which the project management system operates.",
      description_2:"Development of the main website for a company, using vuejs, vuebootstrap, and nutxjs, in addition to applying design concepts and UX/UI.",
      description_3: "Of course this online cv was also built by me, using vuejs and nutxjs, in addition to notions of bootstrap and usability.",


    }
  }
}
</script>
