<template>
  <div class="wrapper">
    <div class="header">
      <div class="logo">
        <img src="@/assets/svg/t_logo.png" alt="logo" />
      </div>
      <div class="navigation">
        <a href="" class="nav-child">home</a>
        <a href="" class="nav-child">find a doctor</a>
        <a href="" class="nav-child">apps</a>
        <a href="" class="nav-child">testimonials</a>
        <a href="" class="nav-child">about us</a>
      </div>
    </div>
  </div>
</template>

<script>
// TODO delete unused classes
// TODO logo to text (not png)
export default {
  name: "VHeader",
  props: {},
};
</script>

<style scoped lang="scss">
.wrapper {
  width: 1200px;
  margin: 0 auto;
}

.header {
  display: flex;
  justify-content: space-between;

  margin-top: 60px;
  margin-bottom: 85px;
}

.navigation {
  display: flex;
  justify-content: space-between;
  width: 545px;

  .nav-child {
    display: flex;
    align-items: center;

    font-family: "Mulish", sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 22.59px;
    color: #1f1534;

    text-align: center;
    text-decoration: none;
    text-transform: capitalize;
  }

  .nav-child:hover {
    text-decoration: underline #1f1534;
    cursor: pointer;
  }

  .nav-child:active {
    cursor: pointer;
  }
}
</style>
