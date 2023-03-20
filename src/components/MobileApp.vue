<template>
  <div class="wrapper">
    <div class="mobile-apps">
      <div class="left-side">
        <h3>Download our mobile apps</h3>
        <div class="description">
          Our dedicated patient engagement app and web portal allow you to
          access information instantaneously (no tedeous form, long calls, or
          administrative hassle) and securely
        </div>
        <div class="button">
          <p>Download</p>
          <img src="@/assets/svg/vector_download.png" alt="download" />
        </div>
      </div>
      <img
        src="@/assets/svg/trafalgar-illustration_mobile_apps.png"
        alt="mobile apps"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "MobileApp",
  props: {},
};
</script>

<style lang="scss" scoped>
.wrapper {
  width: 1200px;
  margin: 0 auto;
}
.mobile-apps {
  display: flex;
  justify-content: space-between;

  margin-bottom: 260px;
}

.left-side {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;

  width: 420px;
}

h3 {
  font-weight: 700;
  font-size: 36px;
  line-height: 48px;

  padding-bottom: 61px;
}

h3::after {
  content: "";
  position: relative;
  display: block;

  bottom: -45px;

  width: 15%;
  height: 2px;
  background-color: #000000;
}

.description {
  font-weight: 300;
  font-size: 18px;
  line-height: 30px;
}

.button {
  display: flex;
  align-items: center;
  justify-content: center;

  width: 200px;
  height: 60px;

  border: 2px solid #458ff6;
  border-radius: 55px;

  font-weight: 700;
  font-size: 18px;
  line-height: 60px;
  color: #458ff6;

  cursor: pointer;

  p {
    padding-right: 14px;
  }
}

.button:active {
  transition: background-color 0.1s ease-out;

  cursor: pointer;

  background-color: #458ff6;
  color: #ffffff;
}
</style>
