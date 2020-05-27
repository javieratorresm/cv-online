
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
                      <div id="works-container" class="sub-headline works-container works-masonry-container clearfix ">
                          <!-- start : works-item -->
                          <b-row  align-h="center" >
                            <b-col sm="12" class="">

                          <div class="works-item works-item-one-third zoom ui web">
                                  <img data-no-retina alt="" title="" class="img-responsive" src="@/assets/img/works/small/01.jpg"/>
                                  <a  class="venobox">
                                      <div class="works-item-inner">
                                          <h3><span class="white font2bold">Ciudad Sur</span></h3>
                                          <div class="row">
                                              <div class="col-md-3">
                                          <p><span class="white font1">Front-end, Vuejs, Nuxtjs, Design, UX, UI, Developer, Web Design, PMO</span></p>
                                          <img src="@/assets/img/fondef.svg" alt="w-40">
                                        </div>

                                          <div class="col-md-6">

                                          <p>{{description_1}}</p>
                                        </div>
                                      </div>

                                      </div>
                                  </a>

                          </div>
                        </b-col>
                          <!-- end : works-item -->




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
      description_1: "I participated in the development of the Healthy living south city Fondef project, I created the concept to be developed on the website, developing it using vuejs, nutxjs, and UX/UI user experience concepts. In addition, I  established the guidelines of the project's social media plan, advising on the creation, content, and other matters related to the design. I am currently the PMO of the technology area, in charge of the team and the 3 software modules in which the project management system operates.",
      description_2:"Development of the main website for a company, using vuejs, vuebootstrap, and nutxjs, in addition to applying design concepts and UX/UI.",
      description_3: "Of course this online cv was also built by me, using vuejs and nutxjs, in addition to notions of bootstrap and usability.",


    }
  }
}
</script>
