<template>
  <div>
    <section id = "intro" class = "space">
      <div class = "d-flex flex-column justify-contetn-center align-items-center text-center">
        <p class = "section-badge color-green">CLIENT-DEVELOPMENT DRIVEN</p>
        
        <h1 class = "page-title text-white my-4 lh-base">
          We Design. We Develop. We Ship. <br/>
          In The Same Day.
        </h1>
        
        <p class = "page-desc lh-lg color-muted">
          We are committed to not making clients wait. We will deliver the work <br/>
          as quickly as possible. Even on the same day. Even so, we do not <br/>
          reduce the quality of our work.
        </p>

        <div class = "d-flex mt-3">
          <div>
            <button type = "button" class = "btn color-button-primary px-5 py-3">Send Quote</button>
          </div>
          <div class="ms-3">
            <button type = "button" class = "btn color-button-light px-5 py-3">Learn More</button>
          </div>
        </div>
      </div>
    </section>

    <section id = "feature-card">
      <div class = "row">
        <div class = "col-4">
          <div class = "card border-0 bg-light">
            <div class="card-body mx-5 my-4">
              <img src = "~/assets/images/icons/icon-figma.png" class = "img-fluid" alt = "icon-figma" loading="lazy">
              <h5 class = "text-white mt-4">Design</h5>
              <div class="color-muted lh-lg">
                The project interface will be designed first, our favorite tool is Figma.
              </div>
            </div>
          </div>
        </div>
        <div class = "col-4">
          <div class = "card border-0 bg-light">
            <div class="card-body mx-5 my-4">
              <img src = "~/assets/images/icons/icon-code.png" class = "img-fluid" alt = "icon-code" loading="lazy">
              <h5 class = "text-white mt-4">Develop</h5>
              <div class="color-muted lh-lg">
                Transform design and write business logic here. Choose the technology you want.
              </div>
            </div>
          </div>
        </div>
        <div class = "col-4">
          <div class = "card border-0 bg-light">
            <div class="card-body mx-5 my-4">
              <img src = "~/assets/images/icons/icon-box.png" class = "img-fluid" alt = "icon-box" loading="lazy">
              <h5 class = "text-white mt-4">Ship</h5>
              <div class="color-muted lh-lg">
                After the work is complete, we will send the project and all its assets to you.
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Sponsored -->
      <div class = "space">
        <hr class = "rectangle">
          <div class = "d-flex justify-content-evenly my-4">
            <div>
              <img src = "/assets/images/logo/logo-github.png" class = "img-fluid" alt = "logo-github" loading = "lazy">
            </div>
            <div>
              <img src = "/assets/images/logo/logo-forbes.png" class = "img-fluid" alt = "logo-forbes" loading = "lazy">
            </div>
            <div>
              <img src = "/assets/images/logo/logo-google.png" class = "img-fluid" alt = "logo-google" loading = "lazy">
            </div>
            <div>
              <img src = "/assets/images/logo/logo-microsoft.png" class = "img-fluid" alt = "logo-microsoft" loading = "lazy">
            </div>
            <div>
              <img src = "/assets/images/logo/logo-facebook.png" class = "img-fluid" alt = "logo-facebook" loading = "lazy">
            </div>
          </div>
        <hr class = "rectangle">
      </div>

    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>