<template >
  <div class="c px-5 cv-resume">
    <div class="">
      <h1 class="">{{title}}</h1>
      <p class="p_b ">{{description}}</p>
    </div>

<div class="cv-description">
  <b-row class="line-bottom ">
    <b-col sm="12" class="">
      <b-row class="">
        <b-col sm="9" class="px-5">
          <div class="description_me ">
          <p class="">{{description_me}}</p>
          </div>
          <div class="curr" v-for="post in posts">
              <b-row class="">
                <b-col sm="4" class="">
                  <div class="">
                    <p class="p_b">{{post.fecha}}</p>
                    <h6>{{post.lugar}}</h6>
                  </div>

                </b-col>
                <b-col sm="8" class="">
                  <div class="">
                    <h4 class="">{{post.title}}</h4>
                    <p class="p_b">{{post.parrafo}}</p>
                  </div>

                </b-col>
              </b-row>
            </div>
        </b-col>
        <b-col sm="3" class="resumes">



        <div class="university pb-3">
          <h5>{{title_ed}}</h5>
          <h6>{{education_c.university}}</h6>
          <h6>{{education_c.years}}</h6>
          <h6>{{education_c.title}}</h6>
          <h5 class="">Courses</h5>
          <h6>Desafio Latam</h6>
          <h6>2019</h6>
          <h6>UX/UI Design</h6>

        </div>

        <div class="skills pb-3">
          <h5>{{tittle_s}}</h5>
          <h6>Front-end development</h6>
          <h6>UI/UX Design</h6>
          <h6>Managing teams</h6>
        </div>

        <div class="contact pb-3">
          <h5>{{tittle_c}}</h5>
          <h6>{{education_d.mail}}</h6>
          <h6>{{education_d.direction}}</h6>
        </div>
        <script type="text/javascript" src="https://platform.linkedin.com/badges/js/profile.js" async defer></script>


        <div class="LI-profile-badge pb-3"  data-version="v1" data-size="medium" data-locale="es_ES" data-type="vertical" data-theme="dark" data-vanity="javiera-torres-9229b7121">
          <h5>Linkedin profile</h5>
          <a class="LI-simple-link" href='https://cl.linkedin.com/in/javiera-torres-9229b7121?trk=profile-badge'>Javiera Torres</a></div>
        </b-col>

      </b-row>




    </b-col>
  </b-row>

</div>



  </div>



</template>

<script>
export default{
  head(){
      return{
      }
    },
  methods:{
  },
  data(){
    return {
      title: "Professional experience",
      description:"On paper this is my career trajectory...",
      description_me:"Computer Engineer specialized in digital marketing, UX/UI design, and community management at Universidad de Santiago de Chile, with proven time-management and collaborative skills developed through university programs and volunteer engagements. Knowledge of various programming languages, database structures, web publishing platforms, and diverse types of software Besides, various language courses, web, and app developments.",
        posts: [
      { fecha: "October 2018 – currently", title: 'Computer Engineer', lugar: "CITIAPS, Santiago, Chile", parrafo: "Currently performing as a Software Engineer specialized in FrontEnd, Project Manager, UX/UI designer, and community manager for Centro de Innovación en Tecnologías de la Información para Aplicaciones Sociales (CITIAPS)" },
      { fecha: "March 2019 – January 2020", title: 'Teacher - Data Structures Analysis', lugar: "Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "" },
      { fecha: "October 2018 – January 2019", title: 'Research Assistant - “Sistema de Acompañamiento e Inserción a la Vida Universitaria” project', lugar: "Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "" },
      { fecha: "March 2018 – July 2019", title: 'Student Assistantship (evening classes) - Data Structures Analysis', lugar: "Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "" },
      { fecha: "May 2018 – December 2018", title: 'Student Assistantship - Software Engineering Project', lugar: "", parrafo: "" },
      { fecha: "March 2018 – December 2019", title: 'Research Assistant - Atómicas USACh project', lugar: " Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "Atómicas USACh is a project funded by the Computer Department to motivate the participation of women in the computer science area. It was a volunteer job" },
      { fecha: "March 2018 – December 2019", title: 'Teacher (evening classes) - Data Structures Analysis', lugar:" Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "" },
      { fecha: "August 2017 – December 2017", title: 'Student Assistantship - Database for Evening class,', lugar:" Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "Planned the laboratory and exercises, answered doubts, developed supporting material, and  performed corresponding assistantships. Ruby on Rails and MySQL were used" },
      { fecha: "August 2017 – December 2017", title: 'Student Assistantship - Formal Language Processing', lugar:" Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "Planned the laboratory and exercises, answered doubts, developed supporting material, and  performed corresponding assistantships.  C language, Bison and Flex were used" },
      { fecha: "April 2015 – November 2018", title: 'Student Assistantship - Data Structures Analysis', lugar:" Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "Supported the Laboratory, answered doubts, developed supporting material and eventually performed  classes. In addition, reviewed and evaluated  students’works who were currently studying. C language and LaTeX were used" },


    ],
    title_ed:'Education',
    education_d:{mail:"javiera.torresm@usach.cl", phone: "", direction:"Santiago, Chile"},
    tittle_c:'Contact',
    education_c:{university:"Universidad de Santiago de Chile", years: "2013-2019", title:"Computer Engineer"},
    tittle_s:"Skills"


    }
  }
}
</script>
