<template>
    <div class="container-fluid d-flex align-items-center mt-5">
      <div class="row w-100">
        <!-- Left Section -->
        <div class="col-md-6 d-flex flex-column justify-content-start text-center text-md-start pt-5">
        <h1 class="fw-bold mb-3">An all-in-one app <br>that makes it easier</h1>
        <p><img src="/static/check.png" alt="Check Icon" class="icon"> Est et in pharetra magna adipiscing ornare aliquam.</p>
        <p><img src="/static/check.png" alt="Check Icon" class="icon"> Est et in pharetra magna adipiscing ornare aliquam.</p>
        <p><img src="/static/check.png" alt="Check Icon" class="icon"> Est et in pharetra magna adipiscing ornare aliquam.</p>
        <a href="#" class="no-underline">Find more about the app -></a>
      </div>






  
        <!-- Right Section -->
        <div class="col-md-6 d-flex justify-content-center align-items-center">
          <img
            src="/static/right_video.png"
            alt="Teach students worldwide demo"
            class="img-fluid"
          />
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "ComponentFour",
  };
  </script>
  
  <style lang="scss" scoped>
  
  .container-fluid {
    max-width: 1200px;
  }

  p i {
    margin-right: 8px;
    color: #007bff; 
  }


  /* Remove underline from anchor tag */
  .no-underline {
    text-decoration: none;
    color: #007bff; 
  }

  .no-underline:hover {
    text-decoration: underline; 
  }


  
  h1 {
    font-size: 3rem;
    line-height: 1.2;
  }
  

  
  @media (max-width: 768px) {
    h1 {
      font-size: 2rem;
    }
  
   
  }
  </style>
