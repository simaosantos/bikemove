<template>
  <footer
    class="footer"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >
    <div class="text-center">
      <div class="row justify-content-md-center">
       
          <div class="col-md-12 col-lg-2">
            <ul>
              <li class="nav-item">
                <a
                  class="nav-link"
                  rel="tooltip"
                  title="Like us on Facebook"
                  data-placement="bottom"
                  href="https://www.facebook.com/BikeMoveViseu/"
                  target="_blank"
                >
                  <i class="fab fa-facebook-square"></i>
                  <p class="d-lg-none d-xl-none">Facebook</p>
                </a>
                <h6>Facebook</h6>
              </li>
              <br>
              <li class="nav-item">
                <a
                  class="nav-link"
                  rel="tooltip"
                  title="Follow us on Instagram"
                  data-placement="bottom"
                  href="https://www.instagram.com/bikemove_/"
                  target="_blank"
                >
                  <i class="fab fa-instagram"></i>
                  <p class="d-lg-none d-xl-none">Instagram</p>
                  <h6>Instagram</h6>
                </a>
              </li>
            </ul>
          </div>
          <div class="col-md-12 col-lg-2">
            <i class="fas fa-phone"></i>
            <ul>
              <li>
                <h6>961 940 549</h6>
              </li>
              <br />
              <li>
                <h6>916 923 849</h6>
              </li>
              <br />
              <li>
                <h6>232 415 337</h6>
              </li>
            </ul>
          </div>
          <div class="col-md-12 col-lg-2">
            <i class="fas fa-map-marker"></i>
            <h6>
              Rua Pedro Alves Cabral 164, <br />
              r/c direito. 3500-169, Viseu
            </h6>
          </div>
          <div class="col-md-12 col-lg-2">
            <i class="fas fa-inbox"></i>
            <h6>bikemovelda@gmail.com</h6>
          </div>
           <div class="col-md-12 col-lg-2"> 
            <i class="far fa-clock"></i>
            <h6>Horários</h6>
            <h7>Segunda a sexta: 10:00 - 19:30</h7>
            <br>
            <h7>Sábado: 09:00 - 13:00</h7>
          </div>
        </div>
      </div>
 
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String,
  },
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>
