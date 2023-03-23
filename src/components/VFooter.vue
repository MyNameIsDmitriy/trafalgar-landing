<template>
  <div class="footer-background">
    <div class="wrapper">
      <div class="footer">
        <div class="about-company">
          <h3 class="logo">
            <img src="@/assets/svg/ellipse-8.png" alt="ellipse">
            <img class="img-on-img" src="@/assets/svg/T.png" alt="t">
            Trafalgar
          </h3>
          <div class="description">
            Trafalgar provides progressive, and affordable healthcare,
            accessible on mobile and online for everyone
          </div>
          <div class="rights">©Trafalgar PTY LTD 2020. All rights reserved</div>
        </div>
        <div class="column">
          <h3>Company</h3>
          <div class="links">
            <a>About</a>
            <a>Testimonials</a>
            <a>Find a doctor</a>
            <a>Apps</a>
          </div>
        </div>
        <div class="column">
          <h3>Region</h3>
          <div class="links">
            <a>Indonesia</a>
            <a>Singapore</a>
            <a>Hongkong</a>
            <a>Canada</a>
          </div>
        </div>
        <div class="column">
          <h3>Help</h3>
          <div class="links">
            <a>Help center</a>
            <a>Contact support</a>
            <a>Instructions</a>
            <a>How it works</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "VFooter",
  props: {},
};
</script>

<style lang="scss" scoped>
.footer-background {
  margin: 0 auto;
  margin-top: 200px;
  min-width: 1200px;
  background: linear-gradient(183.41deg, #67c3f3 -8.57%, #5a98f2 82.96%);
}
.wrapper {
  width: 1200px;
  margin: 0 auto;
}

.footer {
  width: 100%;
  display: flex;
  justify-content: space-between;

  padding: 120px 0 113px;
  width: 100%;

  color: #ffffff;
}

.about-company {
  display: flex;
  flex-direction: column;

  width: 391px;
}

.logo {
  display: flex;
  align-items: center;
  font-weight: 700;
  font-size: 24px;
  line-height: 30px;
}

.img-on-img {
  position: relative;
  left: -29px;
  z-index: 1;
}

.description {
  padding-top: 22px;
  padding-bottom: 30px;

  font-weight: 300;
  font-size: 18px;
  line-height: 28px;
}

.rights {
  font-weight: 300;
  font-size: 16px;
  line-height: 28px;
}

.column {
  width: 150px;

  h3 {
    font-weight: 700;
    font-size: 20px;
    line-height: 60px;
  }
}

.links {
  display: flex;
  flex-direction: column;
}

.links a {
  text-decoration: none;

  font-weight: 300;
  font-size: 18px;
  line-height: 38px;
}

a:hover {
  cursor: pointer;
}
</style>
