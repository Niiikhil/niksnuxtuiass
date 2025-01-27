<template>
    <div class="hero-section">
      <div class="content-container">
        <h1 class="title">Join a world of learning</h1>
        <p class="description">
          Malesuada ut aliquam at ac est nisi, interdum etiam dignissim.<br />
          Risus elit et fringilla habitant ut facilisi.
        </p>
        <button class="cta-button">Sign Up Now</button>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "ComponentNine",
  };
  </script>
  
  <style scoped>
  .hero-section {
    background-image: url('https://ace-submission-dev-v2.s3.ap-south-1.amazonaws.com/1738006007_129_yellow.png');

    background-size: cover;
    background-position: center;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    text-align: center;
    padding: 2rem;
  }
  
  .content-container {
    padding: 1.5rem;
    border-radius: 10px;
    max-width: 500px;
    text-align: center;
  }
  
  .title {
    font-size: 2rem;
    font-weight: 700;
    color: #333;
    margin-bottom: 1rem;
  }
  
  .description {
    font-size: 1rem;
    color: #555;
    line-height: 1.5;
    margin-bottom: 1.5rem;
  }
  
  .cta-button {
    background-color: #f97316; /* Orange color */
    color: #fff;
    font-size: 1rem;
    font-weight: 600;
    border: none;
    border-radius: 5px;
    padding: 0.75rem 1.5rem;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  
  .cta-button:hover {
    background-color: #ea580c; /* Slightly darker orange */
  }
  </style>
  