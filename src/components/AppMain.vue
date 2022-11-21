<script>
export default {
  name: "AppMain",
};
</script>

<template>
  <div class="container mt-5">
    <div class="small-container">
      <div class="title-hero pt-5">
        <h5>
          Let Passion and determination be your guide along the way and develop
          at your own pace that's comfortable.
        </h5>
        <small><strong>FANNIE MORENO</strong></small>
        <small><p>/Founder & CEO</p></small>
      </div>
      <div class="numbers mt-5">
        <div class="text-center">
          <h2><Strong class="numers__color">1926</Strong></h2>
          <small><h6>FANNIE MORENO</h6></small>
        </div>
        <div class="text-center">
          <h2><Strong>1926</Strong></h2>
          <small><h6>FANNIE MORENO</h6></small>
        </div>
        <div class="text-center">
          <h2><Strong>1926</Strong></h2>
          <small><h6>FANNIE MORENO</h6></small>
        </div>
        <div class="text-center">
          <h2><Strong>1926</Strong></h2>
          <small><h6>FANNIE MORENO</h6></small>
        </div>
      </div>
      <div class="service-section mt-5">
        <div class="left-side">
          <div class="box">
            <h5 class="box__title">Graphic Design</h5>
            <small
              ><p class="box__parag">
                Have a passion for graphics and arts? Show your talents with
                confidence and self-assertiveness.
              </p></small
            >
            <img
              class="img-card"
              src="../assets/images/home-6-service-image-01.png"
              alt="" />
          </div>
          <div class="box-second">
            <h5 class="box__title">Graphic Design</h5>
            <small
              ><p class="box__parag">
                Have a passion for graphics and arts? Show your talents with
                confidence and self-assertiveness.
              </p></small
            >
            <img
              class="img-card"
              src="../assets/images/home-6-service-image-01.png"
              alt="" />
          </div>
          <div class="box">
            <h5 class="box__title">Graphic Design</h5>
            <small
              ><p class="box__parag">
                Have a passion for graphics and arts? Show your talents with
                confidence and self-assertiveness.
              </p></small
            >
            <img
              class="img-card"
              src="../assets/images/home-6-service-image-01.png"
              alt="" />
          </div>
          <div class="box-fourth">
            <h5 class="box__title">Graphic Design</h5>
            <small
              ><p class="box__parag">
                Have a passion for graphics and arts? Show your talents with
                confidence and self-assertiveness.
              </p></small
            >
            <img
              class="img-card"
              src="../assets/images/home-6-service-image-01.png"
              alt="" />
          </div>
        </div>
        <div class="right-side">
          <p>TOGETHER WE CAN CREATE</p>
          <h3>Services We Can Provide For Our Clients</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.title-hero {
  width: 50%;
  text-align: center;
  margin: 0 auto;
}
.numbers {
  display: flex;
  justify-content: space-around;
  strong {
    color: #1fad96;
  }
}
.service-section {
  display: flex;
  .left-side {
    position: relative;
    width: 50%;
    display: flex;
    flex-wrap: wrap;
    padding-left: 1rem;

    .box,
    .box-second,
    .box-fourth {
      border: 1px solid gainsboro;
      border-radius: 10px;
      width: 9rem;
      margin: 0.4rem;

      // right: 20%;
      // bottom: -60%;
      .box__title {
        padding-left: 0.5rem;
        padding-top: 1rem;
        font-size: small;
      }
      .box__parag {
        padding-left: 0.5rem;
        font-size: xx-small;
        text-align: start;
      }

      .img-card {
        width: 100%;
      }
      .box-second {
        top: 5rem;
        position: absolute;
      }

      .right-side {
        margin: auto;
      }

      // padding-bottom: 5.6rem;
    }
  }
}
</style>
