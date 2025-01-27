
<template>
  <div>
    <nav class="navbar navbar-expand-lg ps-5">
      <div class="container-fluid d-flex">
        <!-- Navbar Brand -->
        <a class="navbar-brand" href="#">
          <img src="/static/logo-colored.png" alt="Logo" width="100" height="auto" />
        </a>
        <!-- Navbar Toggle Button -->
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <!-- Collapsible Navbar Content -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0 gap-5">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Products</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#">Solutions</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#">Pricing</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Resources
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <hr class="dropdown-divider" />
                </li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li>
          </ul>

          <!-- Right-Aligned Items -->
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0 gap-3">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Login</a>
            </li>
            <li class="nav-item">
              <button class="btn btn-outline-dark" type="button">
                Sign Up Now
              </button>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

  
  <script>
  export default {
    name: "Navbar",
  };
  </script>
  
  <style scoped>
  /* Custom styles if needed */
  .navbar {
    background-color: #ffffff; /* Light background color */
  }
  
  /* Adjust padding and layout for mobile screens */
  @media (max-width: 767px) {
    .navbar-nav {
      text-align: center;
      width: 100%;
      padding-left: 0;
      padding-right: 0;
    }
  
    .navbar-toggler {
      margin-right: 0;
    }
  
    /* Ensure the dropdown menu is aligned properly on mobile */
    .dropdown-menu {
      width: 100%;
    }
  
    .navbar-collapse {
      flex-grow: 1;
      justify-content: flex-end;
    }
    
    /* Style for 'Sign Up Now' button */
    .navbar-collapse .btn-outline-dark {
      width: 100%; /* Full width button on mobile */
      margin-top: 10px;
    }
  }
  </style>
  