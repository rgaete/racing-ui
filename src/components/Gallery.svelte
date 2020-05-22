  <script>
  import Carousel from "@beyonk/svelte-carousel";
  import { ChevronLeftIcon, ChevronRightIcon } from "svelte-feather-icons";
</script>

<style>
</style>

<div class="custom-content">
  <div class="site-content">
    <div class="container">
      <div class="row">
        <div class="content col-md-12">
          <div class="card card--clean">
            <header class="card__header card__header--has-filter">
              <h4>Nuestros recuerdos</h4>
            </header>
            <div class="card__content">
              <Carousel draggable = false >
                <span class="control" slot="left-control">
                  <ChevronLeftIcon />
                </span>
                <div class="slide-content">
                  <img
                    alt="Racing 1"
                    src="assets/images/gallery/racing1.jpg" />
                </div>
                <div class="slide-content">
                  <img
                    alt="segunda imagem"
                    src="assets/images/gallery/racing2.jpg" />
                </div>
                <div class="slide-content">
                  <img
                    alt="terceira imagem"
                    src="assets/images/gallery/racing3.jpg" />
                </div>
                <div class="slide-content">
                  <img
                    alt="quarta imagem"
                    src="assets/images/gallery/racing4.jpg" />
                </div>
                  <img 
                    src="assets/images/gallery/racing1.jpg" 
                    alt="Someone is having tough time">
                <div class="slide-content">
                  <img
                    alt="quinta imagem"
                    src="assets/images/gallery/racing6.jpg" />
                </div>
                <span class="control" slot="right-control">
                  <ChevronRightIcon />
                </span>
              </Carousel>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

 
    