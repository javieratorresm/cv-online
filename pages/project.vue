<template>
        <div class="c">
        <section class="">
          <b-row align-h="center" >

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
                  <div class="card" >
                    <img src="@/assets/img/mia2.png" class="card-img-top" alt="image profile">
                    <div class="card-body">
                        <h6 class="card-title ">Project 1</h6>
                        <p  class="card-title-p">Santiago, Chile</p>
                        <p class="black">
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.                          </p>
                          <a href="https://www.linkedin.com/in/javiera-torres" class="btn btn-info">Linkedin</a>
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
  components: {
  },
  data() {
    return {
      tags: ["Front-end", "Vuejs", "Nuxtjs", "Project", "Design", "UX", "UI", "Developer", "Web Design", ""],
    };
  },
};
</script>
