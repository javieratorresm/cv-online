<template>
        <div class="c">
        <section class="">
          <b-row align-h="center" >

            <b-col cols="12" md="2" class="justify-content-center">
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
            <b-row>
              <b-col cols="12" md="4" class="justify-content-center">
                <div class="">
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
              </div>
              </b-col>
              <b-col cols="10" md="4" class="justify-content-center">
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
              <b-col cols="12" md="4"  class="justify-content-center">
                <div class="">
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
               </div>
          </b-col>
           <b-col cols="12" md="4"  class="justify-content-center">
            <div class="">
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

         </div>
         </b-col>
            </b-row>
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
      tags: ["Front-end", "Vuejs", "Nuxtjs", "Project", "Design", "UX", "UI", "Developer", "Web Design"],
    };
  },
};
</script>
