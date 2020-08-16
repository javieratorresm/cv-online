<template>
  <div  class="inicio">
    <header class="">
      <div class="">
         <b-navbar  class="nav " toggleable="true" variant="dark" type="dark" >
           <b-navbar-toggle class="ml-auto nav-tog" target="nav-collapse" v-onclick=""></b-navbar-toggle>
           <b-navbar-brand class="dark" href="">
        </b-navbar-brand>
        <b-collapse id="nav-collapse" is-nav >
           <b-navbar-nav class="flex-row ml-md-auto d-md-flex  " >
             <b-nav-item  class="ml-auto px-2" href="/">Home</b-nav-item>
             <b-nav-item  class="px-3" href="/about">About</b-nav-item>
             <b-nav-item  class="px-3" href="/project-card" >Projects</b-nav-item>
            <!-- <b-nav-item  class="px-3" href="mailto:javiera.torresm@usach.cl">Contact</b-nav-item>-->
           </b-navbar-nav>
         </b-collapse>
       </b-navbar>
        </div>
       </header>

          <nuxt />

          <footer class="c">
            <b-row>
              <b-col sm="12" class="m-2">
                <a class="rrss" href="https://www.linkedin.com/in/javiera-torres/">
                  <i class=" fa fa-linkedin fa-2x "></i>
                </a>
                <a class="rrss" href="https://github.com/javieratorresm">
                  <i class="rrss fa fa-github fa-2x"></i>
                </a>
                <a class="rrss" href="mailto:javiera.torresm@usach.cl"><i class=" rrss fa fa-envelope fa-2x"></i>
                </a>
              </b-col>
            </b-row>
           </footer>
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
    };
  },
};
</script>
