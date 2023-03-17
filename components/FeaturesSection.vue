<template>
  <div id="featuresContainer" class="">
    <div class="container">
      <!-- Feature Header -->
      <div class="text-center text-lg-start mb-5 pb-3">
        <h1 class="display-5 mb-4">
          Why choose Easybank? 
        </h1>

        <p class="fs-5 col-lg-6 contentText">
          We leverage Open Banking to turn your bank account into your financial hub. 
          Control your finances like never before. 
        </p>
      </div>
      
      <div class="d-flex flex-column flex-md-row justify-content-lg-between col-12 flex-wrap">

        <!-- Feature One -->
        <div class="text-center text-lg-start col-md-6 featureItem col-lg-3">
          <!-- Feature icon -->
          <div class="mb-4">
            <img id="" src="icons\icon-online.svg" class="img-fluid mw-100" alt="online_banking_icon">
          </div>
          
          <h4 class="mb-4">
            Online Banking 
          </h4>

          <p class="contentText col-lg-10">
            Our modern web and mobile applications allow you to keep track of your finances 
            wherever you are in the world. 
          </p>
        </div>
        
        <!-- Feature Two -->
        <div class="text-center text-lg-start col-md-6 featureItem col-lg-3">
          <!-- Feature icon -->
          <div class="mb-4">
            <img id="" src="icons\icon-budgeting.svg" class="img-fluid mw-100" alt="simple_budgeting_icon">
          </div>

          <h4 class="mb-4">
            Simple Budgeting 
          </h4>

          <p class="contentText col-lg-10">
            See exactly where your money goes each month. 
            Receive notifications when you’re close to hitting your limits. 
          </p>
        </div>
        
        <!-- Feature Three -->
        <div class="text-center text-lg-start col-md-6 featureItem col-lg-3">
          <!-- Feature icon -->
          <div class="mb-4">
            <img id="" src="icons\icon-onboarding.svg" class="img-fluid mw-100" alt="easy_onboarding_icon">
          </div>

          <h4 class="mb-4">
            Fast Onboarding 
          </h4>

          <p class="contentText col-lg-10">
            We don’t do branches. 
            Open your account in minutes online and start taking control of your finances right away.
          </p>
        </div>
        
        <!-- Feature Four -->
        <div class="text-center text-lg-start col-md-6 featureItem col-lg-3">
          <!-- Feature icon -->
          <div class="mb-4">
            <img id="" src="icons\icon-api.svg" class="img-fluid mw-100" alt="open_api_icon">
          </div>

          <h4 class="mb-4">
            Open API  
          </h4>

          <p class="contentText col-lg-10">
            Manage your savings, investments, pension, and much more from one account. 
            Tracking your money has never been easier.
          </p>
        </div>

      </div>
    </div>

  </div>  
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.featureItem{
    // @media (max-width: 992px) and (min-width: 768px) {
    @media (max-width: 992px) {
      margin-bottom: 50px;
      // border: 2px solid blue !important;
    }
  }

</style>