<template>
    <div class="container my-5">
      <!-- Heading with Buttons -->
      <div class="d-flex justify-content-between align-items-center">
        <div class="heading text-start">
          <p>What everyone says</p>
        </div>
        <div class="d-none d-md-flex gap-3">
          <button
            class="btn"
            type="button"
            data-bs-target="#testimonialCarousel"
            data-bs-slide="prev"
          >
            <img src="/static/button_left.png" alt="Previous" class="img-fluid" />
          </button>
          <button
            class="btn"
            type="button"
            data-bs-target="#testimonialCarousel"
            data-bs-slide="next"
          >
            <img src="/static/button_right.png" alt="Next" class="img-fluid" />
          </button>
        </div>
      </div>
      <!-- Carousel -->
      <div id="testimonialCarousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <!-- Boxes -->
          <div class="carousel-item active">
            <div class="row g-4">
              <div
                class="col-12 col-md-4"
                v-for="(item, index) in testimonials.slice(0, 3)"
                :key="index"
              >
                <div class="testimonial-box p-4 rounded shadow">
                  <p class="testimonial-text">{{ item.text }}</p>
                  <div class="d-flex align-items-center mt-4">
                    <div class="logo-circle bg-light rounded-circle me-3">
                      <img src="/static/logo_two.png" alt="Logo" class="img-fluid" />
                    </div>
                    <div>
                      <p class="mb-0 fw-bold">{{ item.name }}</p>
                      <small class="text-muted">{{ item.designation }}</small>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row g-4">
              <div
                class="col-12 col-md-4"
                v-for="(item, index) in testimonials.slice(3, 6)"
                :key="index"
              >
                <div class="testimonial-box p-4 rounded shadow">
                  <p class="testimonial-text">{{ item.text }}</p>
                  <div class="d-flex align-items-center mt-4">
                    <div class="logo-circle bg-light rounded-circle me-3">
                      <img src="/static/logo_two.png" alt="Logo" class="img-fluid" />
                    </div>
                    <div>
                      <p class="mb-0 fw-bold">{{ item.name }}</p>
                      <small class="text-muted">{{ item.designation }}</small>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "ComponentSeven",
    data() {
      return {
        testimonials: [
          {
            text: "Lacus vestibulum ultricies mi risus, duis non, volutpat nullam non. Magna congue nisi maecenas elit aliquet eu sed consectetur. Vitae quis cras vitae praesent morbi adipiscing purus consectetur mi.",
            logo: "/static/logo_one.png",
            name: "John Doe",
            designation: "Software Engineer",
          },
          {
            text: "Lacus vestibulum ultricies mi risus, duis non, volutpat nullam non. Magna congue nisi maecenas elit aliquet eu sed consectetur. Vitae quis cras vitae praesent morbi adipiscing purus consectetur mi.",
            logo: "/static/logo_two.png",
            name: "Jane Smith",
            designation: "Product Manager",
          },
          {
            text: "Lacus vestibulum ultricies mi risus, duis non, volutpat nullam non. Magna congue nisi maecenas elit aliquet eu sed consectetur. Vitae quis cras vitae praesent morbi adipiscing purus consectetur mi.",
            logo: "/static/logo_one.png",
            name: "Robert Brown",
            designation: "Designer",
          },
          {
            text: "Lacus vestibulum ultricies mi risus, duis non, volutpat nullam non. Magna congue nisi maecenas elit aliquet eu sed consectetur. Vitae quis cras vitae praesent morbi adipiscing purus consectetur mi.",
            logo: "/static/logo_two.png",
            name: "Emily Davis",
            designation: "Marketer",
          },
          {
            text: "Lacus vestibulum ultricies mi risus, duis non, volutpat nullam non. Magna congue nisi maecenas elit aliquet eu sed consectetur. Vitae quis cras vitae praesent morbi adipiscing purus consectetur mi.",
            logo: "/static/logo_one.png",
            name: "Michael Wilson",
            designation: "Analyst",
          },
          {
            text: "Lacus vestibulum ultricies mi risus, duis non, volutpat nullam non. Magna congue nisi maecenas elit aliquet eu sed consectetur. Vitae quis cras vitae praesent morbi adipiscing purus consectetur mi.",
            logo: "/static/logo_two.png",
            name: "Sarah Johnson",
            designation: "Consultant",
          },
        ],
      };
    },
  };
  </script>
  
  <style scoped>
  .heading {
    font-size: 3rem;
    font-weight: 800;
  }
  
  .testimonial-box {
    background-color: #fff;
    box-shadow: 0 -4px 4px rgba(0.1, 0.1, 0.1, 0.1), 4px 4px 12px rgba(0, 0, 0, 0.2);
  }
  
  .testimonial-text {
    font-size: 1rem;
    color: #4a5568;
  }
  
  .logo-circle {
    width: 50px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
  }
  
  .logo-circle img {
    width: 100%;
    height: auto;
  }
  
  @media (max-width: 767px) {
    .col-md-4 {
      flex: 0 0 100%;
      max-width: 100%;
    }
  }
  </style>
  