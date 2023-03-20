<template>
  <div class="wrapper">
    <div class="our-article">
      <div class="header">Check out our latest article</div>
      <div class="articles">
        <div class="article">
          <img src="@/assets/svg/our-articles-1.png" alt="our articles" />
          <div class="description">
            <h3>Disease detection, check up in the laboratory</h3>
            <div class="info">
              In this case, the role of the health laboratory is very important
              to do a disease detection...
            </div>
            <div class="read-more">
              <p>Read more</p>
              <img
                src="@/assets/svg/arrow-rigth-active.png"
                alt="arrow right"
                width="14"
                height="9"
              />
            </div>
          </div>
        </div>
        <div class="article">
          <img src="@/assets/svg/our-article-2.png" alt="our articles" />
          <div class="description">
            <h3>Herbal medicines that are safe for consumption</h3>
            <div class="info">
              Herbal medicine is very widely used at this time because of its
              very good for your health...
            </div>
            <div class="read-more">
              <p>Read more</p>
              <img
                src="@/assets/svg/arrow-rigth-active.png"
                alt="arrow right"
                width="14"
                height="9"
              />
            </div>
          </div>
        </div>
        <div class="article">
          <img src="@/assets/svg/our-article-3.png" alt="our articles" />
          <div class="description">
            <h3>Natural care for healthy facial skin</h3>
            <div class="info">
              A healthy lifestyle should start from now and also for your skin
              health. There are some...
            </div>
            <div class="read-more">
              <p>Read more</p>
              <img
                src="@/assets/svg/arrow-rigth-active.png"
                alt="arrow right"
                width="14"
                height="9"
              />
            </div>
          </div>
        </div>
      </div>
      <div class="button">
        <p>View all</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "OurArticle",
  props: {},
};
</script>

<style lang="scss" scoped>
.wrapper {
  width: 1200px;
  margin: 0 auto;
}

.header {
  display: flex;
  justify-content: center;
  align-items: center;

  margin-bottom: 100px;

  font-weight: 700;
  font-size: 36px;
  line-height: 56px;
}

.header::after {
  content: "";
  position: relative;
  display: block;

  bottom: -50px;
  left: -250px;

  width: 4%;
  height: 2px;
  background-color: #000000;
}

.articles {
  display: flex;
  justify-content: space-evenly;

  margin-bottom: 70px;
}

.article {
  width: 350px;

  background: #ffffff;
  box-shadow: 10px 40px 50px rgba(229, 233, 246, 0.4);
  border-radius: 20px;

  img {
    border-radius: 20px 20px 0px 0px;
  }
}

.description {
  width: 265px;

  padding-top: 21px;
  padding-bottom: 35px;
  margin: 0 auto;
}

.info {
  padding-top: 12px;

  font-weight: 300;
  font-size: 16px;
  line-height: 28px;
  color: #7d7987;
}

.read-more {
  display: flex;

  padding-top: 25px;

  img {
    align-items: center;
    align-self: center;
  }

  p {
    padding-right: 15px;

    font-weight: 600;
    font-size: 17px;
    line-height: 28px;
    color: #4089ed;

    cursor: pointer;
  }
}

h3 {
  font-weight: 700;
  font-size: 21px;
  line-height: 32px;
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

  margin: 0 auto;
}

.button:active {
  transition: background-color 0.1s ease-out;

  cursor: pointer;

  background-color: #458ff6;
  color: #ffffff;
}
</style>
