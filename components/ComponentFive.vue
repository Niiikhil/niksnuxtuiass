<template>
    <div class="container-fluid d-flex align-items-center mt-5">
      <div class="row w-100">
        <!-- Left Section -->
        <div class="col-md-6 d-flex justify-content-center align-items-center">
          <img
            src="/static/students.png"
            alt="Teach students worldwide demo"
            class="img-fluid"
          />
        </div>



        
  
        <!-- Right Section -->
        <div class="col-md-6 d-flex flex-column justify-content-center text-center text-md-start ps-2">
          <h1 class="fw-bold mb-3">Meet international <br>students & teachers</h1>
          <p class="mb-4">
            Morbi sit egestas dignissim pharetra, sed amet. Tempus justo <br>senectus risus ac vel, velit, nunc. Eget commodo eget in aliquam <br>facilisi facilisi nec magna hendrerit. Placerat ipsum sit tellus urna, <br>faucibus aenean lorem faucibus integer.
          </p>
          
          <a href="#" class="anchortag">Explore teachers and students -></a>
        </div>
        
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "ComponentFive",
  };
  </script>
  
  <style lang="scss" scoped>
  
  .container-fluid {
    max-width: 1200px;
  }
  .anchortag{
    text-decoration: none;
    color: #007bff;
  }
  
  h1 {
    font-size: 3rem;
    line-height: 1.2;
  }
  
  
  
  @media (max-width: 768px) {
    h1 {
      font-size: 2rem;
    }
  
    p {
      font-size: 0.9rem;
    }
  
   
  }
  </style>
  