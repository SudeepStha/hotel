<template>
  <template-view>

    <!-- Carousel -->
    <carousel-component />

    <!-- Introduction Section -->
    <section class="py-5">
      <div class="container">
        <div class="row g-4">
          <div class="col-md-4 order-md-last ">
            <img src="@/assets/room.jpg" alt="" srcset="" class="img-fluid rounded">
          </div>
          <div class="col-md-8">
            <h1>REDEFINES THE LUXURY HOSPITALITY EXPERIENCE</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem harum deleniti blanditiis sunt porro in, officiis excepturi velit recusandae aspernatur! Nesciunt quia porro excepturi, ipsum aut possimus libero. Ea quidem, culpa repudiandae at non nemo a, enim excepturi doloribus suscipit debitis. Beatae non temporibus, modi molestias dicta excepturi reprehenderit tempora.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section class="py-5">
      <div class="container bg-light">
        <div class="row g-4">
          <div class="col-md-4">
            <img src="@/assets/room.jpg" alt="" class="img-fluid rounded">
          </div>
          <div class="col-md-8">
            <h1>DISCOVERS OUR ROOMS EXPLORE ROOMS & SUITS</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate pariatur nihil voluptas at sapiente itaque delectus in nemo repellat ad minus animi vel porro, accusamus expedita assumenda nobis dignissimos magni? Tempora, odio quasi laborum quo est laudantium amet eum illum eius repellendus impedit qui modi. Esse blanditiis quibusdam eligendi assumenda.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section class="py-5">
      <div class="container">
        <div class="row g-4">
          <div class="col-md-4 order-md-last">
            <img src="@/assets/room.jpg" alt="" class="img-fluid rounded">
          </div>
          <div class="col-md-8">
            <h1>DISCOVERS OUR ROOMS EXPLORE ROOMS & SUITS</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate pariatur nihil voluptas at sapiente itaque delectus in nemo repellat ad minus animi vel porro, accusamus expedita assumenda nobis dignissimos magni? Tempora, odio quasi laborum quo est laudantium amet eum illum eius repellendus impedit qui modi. Esse blanditiis quibusdam eligendi assumenda.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section class="py-5">
      <div class="container bg-light">
        <div class="row g-4">
          <div class="col-md-4">
            <img src="@/assets/room.jpg" alt="" class="img-fluid rounded">
          </div>
          <div class="col-md-8">
            <h1>DISCOVERS OUR ROOMS EXPLORE ROOMS & SUITS</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate pariatur nihil voluptas at sapiente itaque delectus in nemo repellat ad minus animi vel porro, accusamus expedita assumenda nobis dignissimos magni? Tempora, odio quasi laborum quo est laudantium amet eum illum eius repellendus impedit qui modi. Esse blanditiis quibusdam eligendi assumenda.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section class="py-5">
      <div class="container">
        <div class="row g-4">
          <div class="col-md-4 order-md-last">
            <img src="@/assets/room.jpg" alt="" class="img-fluid rounded">
          </div>
          <div class="col-md-8">
            <h1>DISCOVERS OUR ROOMS EXPLORE ROOMS & SUITS</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate pariatur nihil voluptas at sapiente itaque delectus in nemo repellat ad minus animi vel porro, accusamus expedita assumenda nobis dignissimos magni? Tempora, odio quasi laborum quo est laudantium amet eum illum eius repellendus impedit qui modi. Esse blanditiis quibusdam eligendi assumenda.</p>
          </div>
        </div>
      </div>
    </section>

  </template-view>
</template>

<script>
import TemplateView from '../views/TemplateView.vue'
import CarouselComponent from '../components/homepage/CarouselComponent.vue'

export default {
  name: 'HomeView',
  components:{
    TemplateView,
    CarouselComponent
  }
}
</script>
