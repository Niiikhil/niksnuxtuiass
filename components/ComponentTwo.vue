<template>
  <div class="container-fluid d-flex align-items-center mt-5">
    <div class="row w-100">
      <!-- Left Section -->
      <div class="col-md-6 d-flex flex-column justify-content-start text-center text-md-start">
        <h1 class="fw-bold mb-3">Teach students worldwide</h1>
        <p class="mb-4">
          Amet nunc diam orci duis ut sit diam arcu, nec. Eleifend proin massa
          tincidunt viverra lectus pulvinar. Nunc ipsum est pellentesque turpis
          ultricies.
        </p>
        <div class="d-flex flex-wrap gap-3 justify-content-center justify-content-md-start mb-5">
          <!-- Sign Up Button -->
          <button class="btn btn-warning text-white fw-bold px-4 py-2">
            Sign Up Now
          </button>
          <!-- View Demo Button -->
          <button
            class="btn btn-outline-secondary d-flex align-items-center px-3 py-2"
          >
            <i class="bi bi-play-circle me-2"></i> View Demo
          </button>
        </div>
        <!-- Trusted Companies -->
        <div class="d-flex flex-wrap gap-4 align-items-center justify-content-center justify-content-md-start">
          <p class="text-muted mb-3 me-3">
            Trusted by <br />
            leading companies:
          </p>
          <img src="/static/company1.png" alt="Company 1 Logo" width="50" />
          <img src="/static/company2.png" alt="Company 2 Logo" width="50" />
          <img src="/static/company3.png" alt="Company 3 Logo" width="50" />
          <img src="/static/company4.png" alt="Company 4 Logo" width="50" />
        </div>
      </div>

      <!-- Right Section -->
      <div class="col-md-6 d-flex justify-content-center align-items-center">
        <img
          src="/static/demo_image.png"
          alt="Teach students worldwide demo"
          class="img-fluid"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ComponentTwo",
};
</script>

<style lang="scss" scoped>

.container-fluid {
  max-width: 1200px;
}

h1 {
  font-size: 3rem;
  line-height: 1.2;
}

p {
  font-size: 1rem;
  margin-bottom: 1rem;
}

button {
  border-radius: 0.375rem;
}

@media (max-width: 768px) {
  h1 {
    font-size: 2rem;
  }

  p {
    font-size: 0.9rem;
  }

  button {
    font-size: 0.875rem;
    padding: 0.5rem 1rem;
  }
}
</style>
