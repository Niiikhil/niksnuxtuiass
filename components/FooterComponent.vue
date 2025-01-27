<template>
    <div class="footer bg-dark text-white py-5">
      <div class="container">
        <div class="row">
          <!-- Logo Column -->
          <div class="col-12 col-md-2 text-center mb-4 mb-md-0">
            <img src="/static/logo-colored.png" alt="Logo" class="img-fluid" />
          </div>
  
          <!-- Product Column -->
          <div class="col-12 col-md-2">
            <p class="fw-bold">Product</p>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">Pricing</a></li>
              <li><a href="#" class="text-white">Overview</a></li>
              <li><a href="#" class="text-white">Browse</a></li>
              <li><a href="#" class="text-white">Accessibility</a></li>
            </ul>
          </div>
  
          <!-- Repeat the same structure for the remaining columns -->
          <div class="col-12 col-md-2">
            <p class="fw-bold">Company</p>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">About Us</a></li>
              <li><a href="#" class="text-white">Careers</a></li>
              <li><a href="#" class="text-white">Press</a></li>
              <li><a href="#" class="text-white">Blog</a></li>
            </ul>
          </div>
  
          <div class="col-12 col-md-2">
            <p class="fw-bold">Support</p>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">Contact</a></li>
              <li><a href="#" class="text-white">FAQs</a></li>
              <li><a href="#" class="text-white">Help Center</a></li>
              <li><a href="#" class="text-white">Terms of Service</a></li>
            </ul>
          </div>
  
          <div class="col-12 col-md-2">
            <p class="fw-bold">Legal</p>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">Privacy Policy</a></li>
              <li><a href="#" class="text-white">Cookie Policy</a></li>
              <li><a href="#" class="text-white">Terms of Use</a></li>
              <li><a href="#" class="text-white">Licensing</a></li>
            </ul>
          </div>
  
          <div class="col-12 col-md-2">
            <p class="fw-bold">Follow Us</p>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">Facebook</a></li>
              <li><a href="#" class="text-white">Twitter</a></li>
              <li><a href="#" class="text-white">LinkedIn</a></li>
              <li><a href="#" class="text-white">Instagram</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "FooterComponent",
  };
  </script>
  
  <style scoped>
  .footer {
    background-color: #334155;
  }
  
  .footer a {
    text-decoration: none;
  }
  
  .footer a:hover {
    text-decoration: underline;
  }
  
  @media (max-width: 576px) {
    .footer .col-12 {
      text-align: center;
    }
  }
  </style>
  