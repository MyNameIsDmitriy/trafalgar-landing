<template>
  <div class="wrapper">
    <div class="our-services">
      <h2 class="header">Our services</h2>
      <div class="description">
        We provide to you the best choiches for you. Adjust it to your health
        needs and make sure your undergo treatment with our highly qualified
        doctors you can consult with us which type of service is suitable for
        your health
      </div>

      <div class="services">
        <div class="service">
          <img
            src="@/assets/svg/search.png"
            alt="search a doctor"
            width="91"
            height="90"
          />
          <h3>Search a doctor</h3>
          <div class="service-description">
            Choose your doctor from thousands of specialist, general, and
            trusted hospitals
          </div>
        </div>

        <div class="service">
          <img
            src="@/assets/svg/online-pharmacy.png"
            alt="online pharmacy"
            width="61"
            height="85"
          />
          <h3>Online pharmacy</h3>
          <div class="service-description">
            Buy your medicines with our mobile application with a simple
            delivery system
          </div>
        </div>

        <div class="service">
          <img
            src="@/assets/svg/consultation.png"
            alt="consultation"
            width="67"
            height="95"
          />
          <h3>Consultation</h3>
          <div class="service-description">
            Free consultation with our trusted doctors and get the best
            recomendations
          </div>
        </div>

        <div class="service">
          <img
            src="@/assets/svg/details.png"
            alt="details info"
            width="91"
            height="90"
          />
          <h3>Details info</h3>
          <div class="service-description">
            Free consultation with our trusted doctors and get the best
            recomendations
          </div>
        </div>
        <div class="service">
          <img
            src="@/assets/svg/emergancy.png"
            alt="emergency care"
            width="91"
            height="90"
          />
          <h3>Emergency care</h3>
          <div class="service-description">
            You can get 24/7 urgent care for yourself or your children and your
            lovely family
          </div>
        </div>
        <div class="service">
          <img
            src="@/assets/svg/tracking.png"
            alt="tracking"
            width="91"
            height="90"
          />
          <h3>Tracking</h3>
          <div class="service-description">
            Track and save your medical history and health data
          </div>
        </div>
      </div>
      <div class="button">
        <p>Learn more</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "OurServices",
  props: {},
};
</script>

<style lang="scss" scoped>
.wrapper {
  width: 1200px;
  margin: 0 auto;
}
.our-services {
  margin-bottom: 221px;
}

.header {
  display: flex;
  justify-content: center;
  align-items: center;

  font-weight: 700;
  font-size: 36px;
  line-height: 56px;

  padding-bottom: 61px;
}

.header::after {
  content: "";
  position: relative;
  display: block;

  bottom: -45px;
  left: -125px;

  width: 4%;
  height: 2px;
  background-color: #000000;
}

.description {
  margin: 0 auto;

  font-weight: 300;
  font-size: 18px;
  line-height: 30px;
  color: #7d7987;

  width: 950px;

  padding-bottom: 80px;
}

.services {
  display: grid;
  grid-template-columns: repeat(3, 14em);
  gap: 1em;
  align-items: center;
  justify-content: center;

  margin-bottom: 70px;
}

.service {
  display: flex;
  flex-direction: column;
  justify-content: center;

  box-shadow: 10px 40px 50px rgba(229, 233, 246, 0.4);
  border-radius: 20px;

  height: 354px;

  padding-left: 39px;
  padding-right: 50px;

  h3 {
    font-weight: 700;
    font-size: 24px;
    line-height: 56px;
    color: #000000;

    margin-top: 23px;
  }
}

.service-description {
  font-weight: 300;
  font-size: 16px;
  line-height: 28px;
  color: #7d7987;
}

.button {
  display: flex;
  align-items: center;
  justify-content: center;

  margin: 0 auto;

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
