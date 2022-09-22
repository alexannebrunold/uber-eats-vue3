<template>
  <div class="restaurant-card">
    <div class="restaurant-card--image" />
    <div class="restaurant-card--informations">
      <div class="namexrating">
        <p>restaurantName</p>

        <span class="rating-circle">
          <p>4.0</p>
        </span>
      </div>
      <p class="hours">Hours</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.restaurant-card {
  width: 420px;
  font-size: 16px;
  

  &--image {
    background-image: url("https://cn-geo1.uber.com/image-proc/resize/eats/format=webp/width=550/height=440/quality=70/srcb64=aHR0cHM6Ly9kMXJhbHNvZ25qbmczNy5jbG91ZGZyb250Lm5ldC8zNzg4MDJiMC1jNTI4LTQ4MjktYjBiNS0wY2M2NDBkZjYzY2QuanBlZw==");
    background-size: cover;
    height: 240px;
  }
  &--informations {
    display: flex;
    flex-direction: column;
    margin-top: 16px;

    .namexrating {
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      font-weight: 600;
    }

    .rating-circle {
      background-color: grey;
      height: 32px;
      min-width: 32px;
      border-radius: 100%;
      align-items: center;
      justify-content: center;
      display: flex;
    }

    .hours {
      margin-top: 8px;
      align-self: flex-start;
      font-size: 14px;
      font-weight: 200;
    }
  }
}
</style>
