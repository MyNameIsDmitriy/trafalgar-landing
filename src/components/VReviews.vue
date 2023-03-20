<template>
  <div class="wrapper">
    <div class="reviews">
      <div class="main">
        <h3 class="header">What our customer are saying</h3>
        <div class="review">
          <div class="account-info">
            <img src="@/assets/svg/profile_img.png" alt="profile image" />
            <div class="info">
              <p class="name">edward newgate</p>
              <p class="status">founder circle</p>
            </div>
          </div>
          <div class="description">
            “Our dedicated patient engagement app and web portal allow you to
            access information instantaneously (no tedeous form, long calls, or
            administrative hassle) and securely”
          </div>
        </div>
      </div>
      <div class="slider">
        <button><span></span></button>
        <button><span></span></button>
        <button><span></span></button>
        <button><span></span></button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "VReviews",
  props: {},
};
</script>

<style lang="scss" scoped>
.wrapper {
  width: 1200px;
  margin: 0 auto;
}
.reviews {
  margin-bottom: 220px;
}

.main {
  display: flex;
  justify-content: space-between;
  flex-direction: column;

  width: 1120px;
  height: 425px;

  background: linear-gradient(208.18deg, #67c3f3 9.05%, #5a98f2 76.74%);
  border-radius: 24px;

  margin: 0 auto;
}

.header {
  align-self: center;

  font-weight: 700;
  font-size: 36px;
  line-height: 48px;
  color: #ffffff;

  padding-top: 64px;
}

.header::after {
  content: "";
  position: relative;
  display: block;

  bottom: -35px;
  left: 225px;

  width: 10%;
  height: 2px;
  background-color: #ffffff;
}

.review {
  display: flex;
  justify-content: space-around;
  align-items: center;

  padding-bottom: 80px;
}

.description {
  font-weight: 400;
  font-size: 19px;
  line-height: 30px;
  color: rgba(255, 255, 255, 0.9);

  width: 420px;
}

.account-info {
  display: flex;
  justify-content: space-between;

  width: 355px;
}

.info {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.name {
  font-weight: 700;
  font-size: 22px;
  color: #ffffff;
}

.status {
  font-weight: 400;
  font-size: 18px;
  color: rgba(255, 255, 255, 0.85);
}

.name,
.status {
  align-items: center;
  justify-content: center;

  line-height: 30px;
  text-transform: capitalize;
}

button {
  border: 0;
  background: transparent;
  cursor: pointer;
}

.slider {
  width: 250px;
  display: flex;
  align-items: center;
  justify-content: center;

  padding-top: 20px;
  margin: 0 auto;
}

.slider button {
  flex: 0 0 42px;
  height: 42px;
  padding: 6px;
  transition: 0.4s;
}

.slider button span {
  display: block;
  height: 30px;
  width: 100%;
  border-radius: 15px;
  background: #82aae3;
  transition: 0.4s;
}

.slider button:focus {
  flex: 0 0 80px;
}

.slider button:focus span {
  background: #438df6;
}
</style>
