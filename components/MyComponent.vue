<template>
    <div class="main-container">
        <div class="center-container">
            <p class="bolder-text">All the tools that you need</p>
        </div>

        <div class="text-container">
            <p>Sit elit feugiat turpis sed integer integer accumsan turpis. Sed suspendisse nec lorem mauris. <br>
                Pharetra, eu imperdiet ipsum ultrices amet, dui sit suspendisse.</p>
        </div>

        




      <div class="image-container"></div>
      <div
        class="foter_logo d-flex align-items-center gap-5 justify-content-center"
        style="background-color: #f1f5f9;"
      >
        <img src="/static/company1.png" alt="Company 1 Logo" class="logo" />
        <img src="/static/company2.png" alt="Company 2 Logo" class="logo" />
        <img src="/static/company3.png" alt="Company 3 Logo" class="logo" />
        <img src="/static/company4.png" alt="Company 4 Logo" class="logo" />
        <img src="/static/company4.png" alt="Company 4 Logo" class="logo" />
        <img src="/static/company4.png" alt="Company 4 Logo" class="logo" />
        <img src="/static/company4.png" alt="Company 4 Logo" class="logo" />
        <img src="/static/company4.png" alt="Company 4 Logo" class="logo" />
        <img src="/static/company4.png" alt="Company 4 Logo" class="logo" />
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "MyComponent",
  };
  </script>
  
  <style scoped>
    .center-container {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background-color: #f1f5f9;
    }
    .text-container {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background-color: #f1f5f9;
    }

    /* Style the text */
    .bolder-text {
    font-size: 3rem; /* Large font size */
    font-weight: 800; /* Maximum boldness */
    margin: 0; /* Remove default margin */
    color: #333; /* Optional text color */
    }

  .image-container {
    background-image: url(/static/noname.png);
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    width: 100vw;
    height: 100vh;
  }
  
  /* Responsive adjustments for smaller devices */
  @media (max-width: 768px) {
    .image-container {
      height: 50vh; /* Adjust height for smaller devices */
    }
  
    .foter_logo {
      flex-wrap: wrap; /* Allow wrapping of logos */
      gap: 10px; /* Reduce spacing between logos */
    }
  
    .foter_logo img {
      width: 40px; /* Scale down logo size */
    }
    .text-container{
        font-size: 1rem; /* Large font size */
        font-weight: 100; /* Maximum boldness */
        margin: 0; /* Remove default margin */
        color: #333; /* Optional text color */

    }
    .bolder-text {
        font-size: 2rem; /* Large font size */
        font-weight: 500; /* Maximum boldness */
        margin: 0; /* Remove default margin */
        color: #333; /* Optional text color */
        }
  }
  
  .foter_logo {
    background-color: #f1f5f9;
    display: flex;
    flex-wrap: wrap; /* Allow logos to wrap if they don't fit in a single row */
    gap: 20px; /* Increase spacing between images */
    padding: 20px; /* Add padding around the container */
    justify-content: center;
  }
  
  .foter_logo .logo {
    margin: 10px; /* Additional space around images */
    width: 50px; /* Default logo size */
    height: auto; /* Maintain aspect ratio */
  }
  
  @media (max-width: 480px) {

    .foter_logo {
        background-color: #f1f5f9;
        display: flex;
        gap: 1px; /* Increase spacing between images */
        padding: 1px; /* Add padding around the container */
        justify-content: center;
    }


    .foter_logo .logo {
      width: 30px; /* Scale logos down further for very small devices */
      gap: 1px;
    }
    
  }
  </style>
  