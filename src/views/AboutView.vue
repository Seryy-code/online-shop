<template>
  <div class="about">
    <HeroSection>
      <div class="primary">
        <div class="cont_text">
          <h1>Shop Smart, Live Better with RoundTable</h1>
          <p>
            Discover a world of convenience with our curated selection of
            top-quality products. Experience reliable shopping that fits your
            lifestyle and needs.
          </p>
        </div>
        <div class="cont_buttons">
          <button class="v1">Shop Now</button>
          <button class="v2">Learn More</button>
        </div>
      </div>
      <div class="secondary">
        <div class="image">
          <img src="@/assets/image.png" alt="" />
        </div>
      </div>
    </HeroSection>
    <HeroSection>
      <div class="primary">
        <h2>
          Discover RoundTable: Your Ultimate Destination for Seamless Online
          Shopping
        </h2>
      </div>
      <div class="secondary">
        <p>
          At RoundTable, we prioritize your shopping experience by offering a
          diverse range of high-quality products tailored to your needs. Our
          platform is designed for convenience and reliability, ensuring you
          find exactly what you're looking for. Join us in redefining online
          shopping with personalized service and competitive prices.
        </p>
      </div>
    </HeroSection>
    <HeroSection>
      <div class="primary">
        <div class="cont_text">
          <h1>Experience Unmatched Benefits at RoundTable</h1>
          <p>
            At RoundTable, we prioritize your shopping experience with
            unbeatable prices and a carefully curated selection. Enjoy a
            seamless journey from browsing to checkout, designed just for you.
          </p>
          <ul>
            <li>
              <h3>Competitive Prices</h3>
              <p>Shop confidently with our low prices that fit your budget.</p>
            </li>
            <li>
              <h3>Curated Selection</h3>
              <p>
                Explore a handpicked range of quality products tailored to your
                needs.
              </p>
            </li>
          </ul>
        </div>
        <div class="cont_buttons">
          <button class="v2">Shop</button>
          <button class="v3">Learn More</button>
        </div>
      </div>
      <div class="secondary">
        <div class="image">
          <img src="@/assets/image.png" alt="" />
        </div>
      </div>
    </HeroSection>
    <HeroSection>
      <div class="primary">
        <h1>Shop the Best Deals Today</h1>
        <p>Discover a world of quality products at great prices.</p>
      </div>
      <div class="secondary">
        <div class="cont_buttons">
          <button class="v1">Shop</button>
          <button class="v2">Browse</button>
        </div>
      </div>
    </HeroSection>
  </div>
</template>
<script>
import HeroSection from "@/components/HeroSection/HeroSection.vue";

export default {
  name: "HomeView",
  components: {
    HeroSection,
  },
};
</script>
