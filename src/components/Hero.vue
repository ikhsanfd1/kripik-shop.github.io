<template>
  <div class="hero">
    <!-- Desktop -->
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Delicious Camilan Menu,</strong>
                <br />in Your Gadget
              </h2>
              <p>Ayo segera pilih dan pesan makanan favorit Anda</p>
              <router-link class="btn btn-lg btn-success" to="/camilan">
                <b-icon-arrow-right></b-icon-arrow-right>Pesan
              </router-link>
            </div>
          </div>
        </div>
        <div class="col d-flex justify-content-end">
          <img src="../assets/images/hero_camilan.png" width="65%" />
        </div>
      </div>
    </div>

    <!-- Mobile -->
    <div class="d-sm-block d-md-none">
      <div class="row mt-4">
        <div class="col-md-6 mb-3">
          <img src="../assets/images/hero_camilan.png" width="65%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Delicious Food Menu,</strong>
                <br />in Your Gadget
              </h2>
              <p>Ayo segera pilih dan pesan makanan favorit Anda</p>
              <button class="btn btn-lg btn-success">
                <b-icon-arrow-right></b-icon-arrow-right>Pesan
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
  
  <script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Hero",
};
</script>
  
  <style>
</style>