
<template>
        <div class="c ">
          <b-row  align-h="" >
              <div class="main-headline container-fluid">
                          <div class="row">
                              <div class="col-md-7 text-left header-caps">
                                <h2 class="  pl-5">Portfolio </h2>
                                <h3 class="pl-5">The collection of my recent projects</h3>
                                <p class="pl-5">Front-end, Vuejs, Nuxtjs, Project, Design, UX, UI, Developer, Web Design
                                </p>
                              </div>
                          </div>

              </div>

                  </b-row>
                      <div class="line-bottom work-dis">
                          <b-row  align-h="center pl-5" >
                            <b-col sm="12" class="">
                            <div class="py-5">
                              <div class="row">
                                  <div class="col-md-3">
                                    <h3><span class="pt-3 white font2bold">Ciudad Sur</span></h3>
                                    <ul class="left pt-3">
                                      <li>Front-end</li>
                                      <li>Vuejs</li>
                                      <li>Nuxtjs</li>
                                      <li>Wordpress</li>
                                      <li>Developer</li>
                                      <li>Web Design</li>
                                      <li>PMO</li>
                                    </ul>
                                  </div>
                                    <div class="col-md-9">
                                  <img alt="" title="" class="img-port-1 w-50  center" src="@/assets/img/ciudadsur1.png"/>
                                    </div>
                                      <div class="pt-3 work-task">
                                          <div class="row">
                                              <div class="col-md-3">
                                          <img class="w-70" src="@/assets/img/fondef.svg" >
                                        </div>

                                          <div class="col-md-7">
                                            <h4><span class="pt-3 white font2bold">Description</span></h4>
                                          <p>{{description_1}}</p>
                                        </div>
                                      </div>

                                      </div>

                          </div>
                        </div>
                        </b-col>
                          <!-- end : works-item -->

                          <b-col sm="12" class="">
                          <div class="py-5">
                            <div class="row">
                                <div class="col-md-3">
                                  <h3><span class="py-3 white font2bold">Portal Center of Innovation and Researh</span></h3>

                              <ul class="left pt-3">
                                <li>Front-end</li>
                                <li>Vuejs</li>
                                <li>Nuxtjs</li>
                                <li>Wordpress</li>

                              </ul>
                          </div>
                          <div class="col-md-9">
                                  <img alt="" title="" class="w-50 img-port-1" src="@/assets/img/citiaps.png"/>
                                </div>

                                </div>
                                      <div class="pt-3 work-task">

                                          <div class="row">
                                              <div class="col-md-3">

                                          <img class="w-70" src="" >
                                        </div>

                                          <div class="col-md-7">
                                            <h4><span class="pt-3 white font2bold">Description</span></h4>
                                          <p>{{description_2}}</p>
                                        </div>
                                      </div>

                                      </div>

                          </div>
                                                  </b-col>


                        </b-row>

                        </div>

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




        </div>

</template>


<script>

export default {
  data() {
    return {
      show: true,
      tags: ["Front-end", "Vuejs", "Nuxtjs", "Project", "Design", "UX", "UI", "Developer", "Web Design", ""],
      description_1: "I participated in the development of the Healthy living south city Fondef project from Chile.   I created the concept to be developed on the website, developing it using vuejs, nutxjs, and UX/UI user experience concepts. In addition, I  established the guidelines of the project's social media plan, advising on the creation, content, and other matters related to the design. I am currently the PMO of the technology area, in charge of the team and the 3 software modules in which the project management system operates.",
      description_2:"Successfully developed the main website for a company, using vuejs, vuebootstrap, nuxtjs, and applied design concepts and UX/UI. Implemented CRM with WordPress, allowing the website to communicate with the API from wp, and letting the user edit the information in a user-friendly environment.",
      description_3: "Of course this online cv was also built by me, using vuejs and nutxjs, in addition to notions of bootstrap and usability.",


    }
  }
}
</script>
