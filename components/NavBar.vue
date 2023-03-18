<template>
  <div id="navBarContainer" class="bg-white">
    <nav class="navbar navbar-expand-lg navbar-white bg-white">
      <div class="container-lg d-flex align-items-top">
        <!-- Logo -->
        <a class="navbar-brand" href="#">
          <img src="images/logo.svg" alt="easybank_logo">
        </a>
        <!-- Menu toggler -->
        <button class="navbar-toggler bg-white p-0 border-0" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation" @click="toggleIcon">
          <i class="fs-1 text-body" :class="menuIcon"></i>
        </button>
        <!-- Links -->
        <div id="navbarNavAltMarkup" class="mobileNavBarContainer collapse navbar-collapse">
          <div class="navbar-nav contentText ms-md-auto mx-auto text-center col-8 col-md-5 d-lg-flex justify-content-lg-between">
            <a class="nav-link" aria-current="page" href="#">Home</a>
            <a class="nav-link" href="#">About</a>
            <a class="nav-link" href="#">Contact</a>
            <a class="nav-link" href="#">Blog</a>
            <a class="nav-link" href="#">Careers</a>
          </div>
          <!-- CTA -->
          <div id="inviteBtn" class="ms-auto">
            <span id="navCtaBtn" class="btn btn-lg text-white border-0 rounded-pill fs-6">
              Request Invite
            </span>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuIcon: "bi-list",
    };
  },
  methods: {
    // toggles menu and close icons
    toggleIcon() {
      if (this.menuIcon === "bi-list") {
        this.menuIcon = "bi-x";
      }
      else {
          this.menuIcon = "bi-list";
      }
    }
    },

}
</script>

<style lang="scss" scoped>

</style>