<template>
    <div class="main-container">
      <div class="box">
        <div class="small-box">
          <img src="/static/content_box_1.png" alt="Content Box 1" />
        </div>
        <div class="small-box">
          <img src="/static/content_box_2.png" alt="Content Box 2" />
        </div>
        <div class="small-box">
          <img src="/static/content_box_3.png" alt="Content Box 3" />
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "ComponentSix",
  };
  </script>
  
  <style scoped>
  /* Main container styling */
  .main-container {
    background-color: #0f172a; /* Background color */
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
  }
  
  /* Rectangular box styling */
  .box {
    display: flex;
    background-color: #0f172a;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap; /* Allow wrapping for responsiveness */
    gap: 20px; /* Space between the small boxes */
    width: 100%; /* Full width */
    max-width: 800px; /* Optional max width for better layout */
  }
  
  /* Small boxes styling */
  .small-box {
    background-color: #0f172a; /* Optional background for small boxes */
    display: flex;

    justify-content: center;
    align-items: center;
    width: 30%; /* 3 boxes side by side */
    max-width: 250px; /* Optional max width for individual boxes */
    aspect-ratio: 1; /* Maintain square boxes */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Optional shadow for aesthetics */
    border-radius: 8px; /* Optional rounded corners */
    overflow: hidden; /* Prevent image overflow */
  }
  
  /* Image styling */
  .small-box img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  /* Responsive Design */
  @media (max-width: 768px) {

    .box{
        display: flex;
      justify-content: center;
      background-color: #0f172a;
      align-items: center;

    }



    .small-box {
      width: 100%; /* One box per row on smaller devices */
      display: flex;
      justify-content: center;
      align-items: center;
      
    }
  }
  </style>
  