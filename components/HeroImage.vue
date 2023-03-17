<template> 
  <div class="">
    <!-- Hero Images -->
    <div id="heroImgContainer" class="mx-auto">
      
      <!-- mobile background -->
      <div id="mobileBckgdContainer" class="d-flex justify-content-center">
        <img id="mobileBackground" src="images\bg-intro-mobile.svg" class="img-fluid" alt="mobile_background_image">
      </div>

      <!-- desktop background -->
      <div id="desktopBckgdContainer">
        <img id="desktopBackground" src="images\bg-intro-desktop.svg" class="img-fluid mw-100" alt="desktop_background_image">
      </div>

      <!-- mockup image -->
      <div id="mockupContainer" class="d-flex justify-content-center">
        <img id="heroMockup" src="images\image-mockups.png" class="img-fluid mw-100 mx-auto" alt="device_mockup_image">
      </div>
    </div>

  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
  computed: {

  }
 
}
</script>

<style lang="scss">

</style>