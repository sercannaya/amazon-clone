<template>
  <div>
    <NavBar />
    <main>
      <div class="listingPage">
        <div class="container-fluid">
          <div class="row">
            <div class="col-xl-2 col-lg-3 md-4 col-sm-4">
              <!-- Side Bar -->
            </div>
            <!-- Main Content -->
            <div class="col-xl-10 col-lg-9 md-8 col-sm-8">
              <FeaturedProduct />
            </div>
          </div>
        </div>
      </div>
    </main>
    <nuxt-link to="/products" class="a-button-buy-again">Add a new product</nuxt-link>
    <Footer />>
  </div>
</template>

<script>
import NavBar from "~/components/NavBar.vue";
import Footer from "../components/Footer.vue";
import FeaturedProduct from "~/components/FeaturedProduct.vue";

export default {
    name: "IndexPage",
    components: { NavBar, Footer, FeaturedProduct }
}
</script>
