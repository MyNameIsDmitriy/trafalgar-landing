<template>
  <div class="wrapper">
    <div class="healthcare-providers">
      <img
        src="@/assets/svg/trafalgar-illustration_sec02_1.png"
        alt="healthcare providers"
      />
      <div class="info">
        <div class="header">Leading healthcare providers</div>
        <div class="description">
          Trafalgar provides progressive, and affordable healthcare, accessible
          on mobile and online for everyone. To us, it's not just work. We take
          pride in the solutions we deliver
        </div>
        <!-- TODO button to component -->
        <div class="button">Learn more</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HealthcareProviders",
  props: {},
};
</script>

<style lang="scss" scoped>
.wrapper {
  width: 1200px;
  margin: 0 auto;
}

.healthcare-providers {
  display: flex;
  justify-content: space-between;

  margin-bottom: 221px;
}

.info {
  display: flex;
  flex-direction: column;
  justify-content: space-around;

  width: 486px;
}

.header {
  font-weight: 700;
  font-size: 36px;
  line-height: 56px;
  color: #000000;

  padding-top: 56px;
}

.header::after {
  content: "";
  position: relative;
  display: block;

  bottom: -25px;

  width: 10%;
  height: 2px;
  background-color: #000000;
}

.description {
  font-weight: 300;
  font-size: 18px;
  line-height: 30px;
  color: #7d7987;
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
}

.button:active {
  transition: background-color 0.1s ease-out;

  cursor: pointer;

  background-color: #458ff6;
  color: #ffffff;
}
</style>
