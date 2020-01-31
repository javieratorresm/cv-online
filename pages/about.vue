<template >
  <div class="c cv-resume">
<h1>{{title}}</h1>
<div class="p-3" v-for="post in posts">
    <b-row class="p-4">
      <b-col sm="4" class="">
          <h5>{{post.fecha}}</h5>
          <h4>{{post.lugar}}</h4>
      </b-col>
      <b-col sm="8" class="">
        <h3>{{post.title}}</h3>
<p>{{post.parrafo}}</p>
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
        posts: [
      { fecha: "October 2018 – currently", title: 'Computer Engineer', lugar: "CITIAPS, Santiago, Chile", parrafo: "Currently performing as a Software Engineer specialized in FrontEnd, Project Manager, UX/UI designer, and community manager for Centro de Innovación en Tecnologías de la Información para Aplicaciones Sociales (CITIAPS)" },
    { fecha: "March 2019 – January 2020", title: 'Teacher - Data Structures Analysis', lugar: "Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "" },
    { fecha: 1, title: 'Research Assistant - “Sistema de Acompañamiento e Inserción a la Vida Universitaria” project,', lugar: "Engineering Faculty, Computer Department, Universidad de Santiago de Chile (USACh)", parrafo: "" },
    { fecha: 1, title: 'Student Assistantship - Software Engineering Project', lugar: "", parrafo: "" },
    { fecha: 1, title: 'My journey with Vue', lugar: "", parrafo: "" }
    ]
    }
  }
}
</script>
