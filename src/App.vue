<script>
import NavbarComponent from './components/NavbarComponent.vue';
import CartComponent from './components/CartComponent.vue';
import ProductsComponent from './components/ProductsComponent.vue';
export default {
  components: {
    NavbarComponent,
    CartComponent,
    ProductsComponent
  }
}
</script>

<template>
  <div class="container">
    <NavbarComponent></NavbarComponent>
    <CartComponent></CartComponent>
    <ProductsComponent></ProductsComponent>
  </div>
</template>

<style lang="scss">
@import "./assets/all.scss";
.table-image {
  height: 100px;
  width: 100px;
  object-fit: cover;
}
.card-img-top {
  height: 200px;
  object-fit: cover;
}
.bi-x-lg {
  margin-left: 8px;
  font-size: 22px;
}
.bi-x-lg:hover {
  color: $danger;
}
</style>
