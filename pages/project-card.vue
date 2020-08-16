
<template>
        <div class="c ">
                          <div class="row">
                              <div class="col-md-12 text-left ">              <div class=" main-headline container-fluid">

                                <h1 class="  pl-5">Portfolio </h1>
                                <h4 class="pl-5">The collection of my recent projects</h4>
                                <p class="pl-5">Front-end, Vuejs, Nuxtjs, Project, Design, UX, UI, Developer, Web Design
                                </p>
                              </div>
                          </div>

              </div>

          <div class="line-bottom p-4">
<b-card-group columns class="card-project">
  <b-card
    title="Human Research"
    img-src="../assets/img/human.png"
    img-alt="preview pag web human research"
    img-top
  >
    <b-card-text class="pt-2">
      {{description_4}}
    </br>
      {{description_4_2}}

    </b-card-text>
    <b-list-group  class=" pt-2 tag">
    <b-list-group-item>Front-end, CSS, HTML</b-list-group-item>
    </b-list-group>
  </b-card>

  <b-card>
    <blockquote class="blockquote mb-0">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
      <footer class="blockquote-footer">
        Someone famous in <cite title="Source Title">Source Title</cite>
      </footer>
    </blockquote>
  </b-card>

  <b-card
    title="Ciudad Sur"
    img-src="../assets/img/ciudadsur1.png"
    img-alt="preview pag web ciudad sur"
    img-top
  >
    <b-card-text class="pt-2">
      {{description_1}}
    </br>
    </b-card-text>
    <b-list-group  class=" pt-2 tag">
    <b-list-group-item>Front-end, CSS, Vuejs, Nuxtjs, Wordpress, Developer, Web Design </b-list-group-item>
    </b-list-group>
  </b-card>
  <b-card title="Ciudad Sur" img-src="../assets/img/fondef.svg" img-alt="logo" img-top img-height-max="350rem"
  >
    <b-card-text>
  Example view responsive  website ciudad sur     </b-card-text>
  </b-card>

  <b-card>
    <blockquote class="blockquote mb-0">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
      <footer class="blockquote-footer">
        Someone famous in <cite title="Source Title">Source Title</cite>
      </footer>
    </blockquote>
  </b-card>

    <b-card img-src="../assets/img/atomicas.png" img-alt="Image" img-top>
      <b-card-text class="mb-2">      {{description_7}}
      </b-card-text>

      <a class="" href="https://youtu.be/IasJcBd8Xtc">Video here</a>

      <template v-slot:footer>
        <small class="text-muted">College Pedro Apóstol, Puente Alto, Santiago. 2019.</small>
      </template>
    </b-card>

    <b-card
      title="Yoi.cl"
      img-src="../assets/img/yoi.png"
      img-alt="preview pag web portal center of innovation"
      img-top
    >
      <b-card-text class="pt-2">
        {{description_2}}
      </br>

      </b-card-text>
      <b-list-group  class=" pt-2 tag">
      <b-list-group-item>Front-end, CSS, Vuejs, Nuxtjs, Wordpress</b-list-group-item>
      </b-list-group>
    </b-card>

  <b-card>

<div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="es_ES" data-type="horizontal" data-theme="dark" data-vanity="javiera-torres"><a class="LI-simple-link" href='https://cl.linkedin.com/in/javiera-torres?trk=profile-badge'>Linkedin Javiera Torres</a></div>

  </b-card>


    <b-card
      title="Portal Center of Innovation and Researh"
      img-src="../assets/img/citiaps.png"
      img-alt="preview pag web portal center of innovation"
      img-top
    >
      <b-card-text class="pt-2">
        {{description_2}}
      </br>

      </b-card-text>
      <b-list-group  class=" pt-2 tag">
      <b-list-group-item>Front-end, CSS, Vuejs, Nuxtjs, Wordpress</b-list-group-item>
      </b-list-group>
    </b-card>

  <b-card>
    <b-card-title>Title</b-card-title>
    <b-card-text>
      This card has supporting text below as a natural lead-in to additional content.
    </b-card-text>
    <b-card-text class="small text-muted">Last updated 3 mins ago</b-card-text>
  </b-card>
  <b-card
    title="Yoi Mi Barrio"
    img-src="../assets/img/yoimibarrio.png"
    img-alt="preview pag web portal center of innovation"
    img-top
  >
    <b-card-text class="pt-2">
      {{description_6}}
    </br>

    </b-card-text>
    <b-list-group  class=" pt-2 tag">
    <b-list-group-item>Front-end, CSS, Vuejs, Nuxtjs, Wordpress</b-list-group-item>
    </b-list-group>
  </b-card>

  <b-card img-src="https://demos.creative-tim.com/argon-dashboard-pro/assets/img/theme/img-1-1000x600.jpg" img-alt="Image" overlay></b-card>


  <b-card
    title="Yoi Ferias"
    img-src="../assets/img/yoiferias.png"
    img-alt="preview pag web portal center of innovation"
    img-top
  >
    <b-card-text class="pt-2">
      {{description_5}}
    </br>

    </b-card-text>
    <b-list-group  class=" pt-2 tag">
    <b-list-group-item>Front-end, CSS, Vuejs, Nuxtjs, Wordpress</b-list-group-item>
    </b-list-group>
  </b-card>


  <b-card img-src="../assets/img/chilewic.jpg" img-alt="Image" img-top>
    <b-card-text class="mb-2">      {{description_8}}
    </b-card-text>

    <a class="" href="https://www.instagram.com/atomicas_usach/">Atomicas USACh</a>

    <template v-slot:footer>
      <small class="text-muted"> Valparaíso, Chile WIC 2018.</small>
    </template>
  </b-card>







</b-card-group>
</div>
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
      description_4: "Developed corporate images, logos, and color palettes. Built a website for a startup according to their requirements, using html and css. ",
      description_4_2: "Created more than 3 social network images, banners and logos adapted to each rrss. And advised on page deployment and security certificates.",
      description_5:"Successfully developed the main website for the social project 'Yoi ferias', using vuejs, vuebootstrap, nuxtjs.",
      description_6:"Successfully developed the main website for the social project 'Yoi Mi Barrio', using vuejs, vuebootstrap, nuxtjs.",
      description_7:"As a woman and an engineer, I feel that I have something to contribute to the future. I actively participate in 'Atomicas USACH,' a project that was born due to the low entry rate of women to the engineering area. In this photo, we are in a school in 'Puente Alto,' presenting opportunities and references for future generations. ",
      description_8:"I represented 'Atomicas Usach' at the Chile WIC event. I presented our work that is about introducing girls and women to the technological area, showing them that there have been and are important women in technology.",


    }
  }
}
</script>
