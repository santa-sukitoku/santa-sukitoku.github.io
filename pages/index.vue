<template>
  <section class="container">
    <div>
      <transition name="page">
        <nuxt />
      </transition>
    </div>
    <body class="all">
      <router-link to="/works/210108">
        <div class="works">
          <img
            src="https://lh3.googleusercontent.com/aEn3EEAz0ST2xhqJtnx_nUxrks6qvlU6yIlN1BkkTN-99HJXjEvLBHnyfnOIYBIfn4oAI2eg8TXDfYLcdlURJERbD3nXnpVG5R6Z4PDvu4wxm1UZSAOCQLfed96J0fCSnkOd1KRGFcM=w2400"
            width="100%"
          />
          <div class="mask">
            <div class="caption">
              <p>website of x-Music Lab</p>
            </div>
          </div>
        </div>
      </router-link>
    </body>
  </section>
</template>

<script>
export default {
  head() {
    return {
      title: "2021",
    };
  },
};
</script>

<style lang="scss" scoped>
.chooseYear a {
  background: linear-gradient(-90deg, #e73c7e, #0e5aff, #23a6d5, #23d5ab);
  background-size: 600% 600%;
  animation: gradientBG 4s ease infinite;
  color: #ffffff;
  text-decoration: none;
  border-bottom: 0px;
}
</style>