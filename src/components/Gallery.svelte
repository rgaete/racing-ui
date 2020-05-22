  <script>
  import Carousel from "@beyonk/svelte-carousel";
  import { ChevronLeftIcon, ChevronRightIcon } from "svelte-feather-icons";
  import { Lightbox } from 'svelte-lightbox';

     
    //Include all titles of your images, this is also used as number that indicate count of sections
    const gallery = [
        'Cat is eating mouse',
        'Bike is driven',
        'JS components are downloaded from npm',
        'This component is being developed'
    ];
    //Have to set to 0 (or image you wish to display as default), otherwise lightbox will not display
    let activeImage = 0;
    //END OF NON EXISTING FEATURE
</script>

<style>
  main {
    height: 75vh;
  }
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
                    src="assets/images/gallery/racing1.png" />
                </div>
                <div class="slide-content">
                  <img
                    alt="segunda imagem"
                    src="assets/images/gallery/racing2.png" />
                </div>
                <div class="slide-content">
                  <img
                    alt="terceira imagem"
                    src="assets/images/gallery/racing3.png" />
                </div>
                <div class="slide-content">
                  <img
                    alt="quarta imagem"
                    src="assets/images/gallery/racing4.png" />
                </div>
                    <Lightbox {gallery} imageId="0" bind:activeImage>
        <img src="assets/images/gallery/racing1.png" alt="Someone is having tough time">
    </Lightbox>
                <div class="slide-content">
                  <img
                    alt="quinta imagem"
                    src="assets/images/gallery/racing6.png" />
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

 
    