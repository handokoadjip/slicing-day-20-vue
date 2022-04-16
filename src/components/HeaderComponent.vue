<template>
  <header class="mb-5">
    <nav class="navbar navbar-light px-lg-2 py-4 mb-5">
      <div class="container-fluid d-flex align-items-center">
        <div class="address w-25">
          <router-link class="fs-6 mb-0 fw-medium" to="#">company</router-link>
        </div>

        <router-link class="navbar-brand text-center fw-medium fs-4" to="#">
          <span class="fw-bold text-primary">></span>valdama
        </router-link>

        <div class="language w-25 text-end">
          <router-link class="fs-6 mb-0 fw-medium" to="#">products</router-link>
        </div>
      </div>
    </nav>

    <section>
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-10">
            <div class="row">
              <div class="col-lg-12">
                <div class="wrapper">
                  <figure class="m-0">
                    <img class="h-image-65vh w-100" src="@/assets/source/image/img-1.jpg" alt="image-1">
                  </figure>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

