<template>
  <div class="restaurant-row">
    <h2 class="title">Nos restaurants</h2>
    <div class="restaurant-row--cards">
      <RestaurantCard v-for="(card, index) in 3" :key="index" />
    </div>
  </div>
</template>

<script>
import RestaurantCard from "./RestaurantCard.vue";

export default {
  name: "RestaurantRow",
  components: {
    RestaurantCard,
  },
};
</script>

<style lang="scss" scoped>
.restaurant-row {
    .title {
        text-align: left;
        font-size: 24px;
        font-weight: 600;
    }
  &--cards {
    margin-top: 24px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
}
</style>
