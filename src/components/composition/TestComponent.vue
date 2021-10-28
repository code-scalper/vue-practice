<template>
  <h2>Hello Reusability</h2>
  <hr />
  <ProductStatus />
  <hr />
  <FeeStatus />
  <hr />
  <SavingStatus />
</template>

<script>
import FeeStatus from "../mixin/FeeStatus";
import ProductStatus from "../mixin/ProductStatus";
import SavingStatus from "../mixin/SavingStatus";
import {} from "vue";
export default {
  name: "TestComponent",
  components: { SavingStatus, ProductStatus, FeeStatus },
};
</script>

<style></style>
