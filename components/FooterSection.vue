<template>
  <div class="footerContainer">
    <div class="container d-md-flex justify-content-md-between align-items-md-start py-5">
      <!-- Logo and Socials -->
      <div class="col-md-3 contentText">
        <!-- Logo -->
        <div class="text-center text-md-start">
          <a class="navbar-brand" href="#">
            <img id="footerLogo" src="icons/footerlogo.svg" alt="easybank_logo">
          </a>
        </div>

        <!-- Socials -->
        <div class="d-flex justify-content-center justify-content-md-start">
          <div class="socialLinks col-7 col-md-11 col-lg-7 d-flex mt-5 justify-content-between">

            <a href="#">
              <img src="icons/icon-facebook.svg" alt="">
            </a>
            <a href="#">
              <img src="icons/icon-youtube.svg" alt="">
            </a>
            <div>
              <img src="icons/icon-twitter.svg" alt="">
            </div>
            <div>
              <img src="icons/icon-pinterest.svg" alt="">
            </div>
            <div>
              <img src="icons/icon-instagram.svg" alt="">
            </div>
          </div>
        </div>

      </div>
      
      <!-- Links -->
      <div class="col-md-4 mt-5 mt-md-0 contentText">
        <div class="col-5 col-md-10 mx-auto d-md-flex text-center text-md-start justify-content-md-between">
          <!-- Link group one -->
          <div>
            <div class="navbar-nav">
                <a class="nav-link pt-md-0" href="#">About</a>
                <a class="nav-link" href="#">Contact</a>
                <a class="nav-link" href="#">Blog</a>
              </div>
          </div>

          <!-- Link group two -->
          <div>
            <div class="navbar-nav">
                <a class="nav-link pt-md-0" href="#">Careers</a>
                <a class="nav-link" href="#">Support</a>
                <a class="nav-link" href="#">Privacy Policy</a>
              </div>
          </div>
        </div>
      </div>

      <!-- CTA AND Copyrigth -->
      <div  class="col-md-4 text-md-end text-center mt-5 mt-md-0 contentText">

        <!-- CTA -->
        <div>
          <div id="footerCTABtn" class="btn border-0 text-white btn-lg rounded-pill fs-6">
                Request Invite
              </div>
        </div>

        <!-- Copyright -->
        <div class="mt-3 mt-md-4 small text-muted">
          <p>© Easybank. All Rights Reserved 2023</p>
        </div>
      </div>

    </div>
      <!-- Attributes -->
      <div class="attribution text-center small contentText">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
        Coded by <a href="#">M. Chase</a>.
  </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

</style>