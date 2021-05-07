<template >
  <!-- Popular Destination -->
  <div class="Popular_Destinations_Class">
    <div class="Popular_Des_Class">
      <div class="title_pop_Class">
        <span>Popular Destinations</span>
      </div>
      <div class="text_pop_Class">
        <span>From historical cities to natural splendours, come see the best of the world!</span>
      </div>
      <svg class="Path_5" viewBox="0 0 192 2">
        <path
          fill="rgba(0,0,0,0)"
          stroke="rgba(120,59,9,1)"
          stroke-width="2px"
          stroke-linejoin="miter"
          stroke-linecap="butt"
          stroke-miterlimit="4"
          shape-rendering="auto"
          class="Path_5_Class"
          d="M 0 0 C 0 0 30 0 78 0 C 126 0 192 0 192 0"
        />
      </svg>
    </div>
  <div class="container-fluid" >
          <VueSlickCarousel v-bind="settings">
            <div class="col-md-2 product pt-4">
              <div>
                <img src="@/assets/images/3.png" alt />
                <div class="description-image-box">
                  <p class="description-image-tittle">Millenium Bridge</p>
                  <p class="description-image-content">London, United Kingdom</p>
                </div>
              </div>
            </div>
            <div class="col-md-2 product pt-4">
              <div>
                <img src="@/assets/images/3.png" alt />
                <div class="description-image-box">
                  <p class="description-image-tittle">Millenium Bridge</p>
                  <p class="description-image-content">London, United Kingdom</p>
                </div>
              </div>
            </div>
            <div class="col-md-2 product pt-4">
              <div>
                <img src="@/assets/images/3.png" alt />
                <div class="description-image-box">
                  <p class="description-image-tittle">Millenium Bridge</p>
                  <p class="description-image-content">London, United Kingdom</p>
                </div>
              </div>
            </div>
            <div class="col-md-2 product pt-4">
              <div>
                <img src="@/assets/images/3.png" alt />
                <div class="description-image-box">
                  <p class="description-image-tittle">Millenium Bridge</p>
                  <p class="description-image-content">London, United Kingdom</p>
                </div>
              </div>
            </div>
            <div class="col-md-2 product pt-4">
              <div>
                <img src="@/assets/images/3.png" alt />
                <div class="description-image-box">
                  <p class="description-image-tittle">Millenium Bridge</p>
                  <p class="description-image-content">London, United Kingdom</p>
                </div>
              </div>
            </div>
            <div class="col-md-2 product pt-4">
              <div>
                <img src="@/assets/images/3.png" alt />
                <div class="description-image-box">
                  <p class="description-image-tittle">Millenium Bridge</p>
                  <p class="description-image-content">London, United Kingdom</p>
                </div>
              </div>
            </div>
            <div class="col-md-2 product pt-4">
              <div>
                <img src="@/assets/images/3.png" alt />
                <div class="description-image-box">
                  <p class="description-image-tittle">Millenium Bridge</p>
                  <p class="description-image-content">London, United Kingdom</p>
                </div>
              </div>
            </div>
        
          </VueSlickCarousel>
           </div>

  </div>
</template>



<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
    name: 'PopularPost',
    components: { VueSlickCarousel },
    data() {
        return {
            settings: {
                dots: true,
               focusOnSelect: true,
               arrows: true,
               infinite: true,
               speed: 500,
               slidesToShow: 3,
               slidesToScroll: 3,
            }
        }
    }
}
</script>
<style lang="css">
.slick-arrow {
    background-color: red;
}
.slick-arrow:hover {
    background-color: red;
} 
</style>