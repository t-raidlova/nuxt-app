<template>
  <section class="masthead" role="img" aria-label="Image Description">
    <h1>
      Nuxt food app
    </h1>
    <nuxt-link to="/restaurants">
      <button>See Restaurants</button>
    </nuxt-link>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.masthead {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  width: 100%;
  height: 75vh;
  padding: 3rem;
  overflow: hidden;
  background-size: cover !important;
  background: radial-gradient(
      ellipse at center,
      #3a0b5054 10%,
      rgba(0, 0, 0, 0) 59%,
      #21d5fd4b 100%
    ),
    url(../assets/headerimg.jpg) no-repeat center center scroll;
}

h1 {
  font-style: normal;
  font-weight: bold;

  color: rgb(255, 255, 255);
  font-size: 8vmin;
  letter-spacing: 0.03em;
  line-height: 1;
  text-shadow: 1px 2px 4px rgba(0, 0, 0, 0.8);
  margin-bottom: 74px;
}
</style>
