<template>
  <div class="virual-healthcare">
    <div class="left-side">
      <h3 class="logo">Virtual healthcare for you</h3>
      <p class="description">
        Trafalgar provides progressive, and affordable healthcare, accessible on
        mobile and online for everyone
      </p>
      <div class="button">Consult today</div>
    </div>
    <div class="right-side">
      <img
        src="@/assets/svg/trafalgar-illustration_1.png"
        alt="trafalgar-image"
      />
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
.virual-healthcare {
  display: flex;
  justify-content: space-between;
}

.left-side {
  display: flex;
  flex-direction: column;

  margin-top: 85px;

  height: 598px;
  width: 427px;

  font-family: "Mulish", sans-serif;
  font-style: normal;

  .logo {
    font-weight: 700;
    font-size: 48px;
    line-height: 56px;
    color: #1f1534;

    margin-bottom: 25px;
  }

  .description {
    font-weight: 300;
    font-size: 21px;
    line-height: 32px;
    color: #7d7987;

    margin-bottom: 45px;
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
  }

  .button:hover {
    cursor: pointer;
  }

  .button:active {
    transition: background-color 0.1s ease-out;

    cursor: pointer;

    background-color: #458ff6;
    color: #ffffff;
  }
}

.right-side {
  width: 693px;
}
</style>
