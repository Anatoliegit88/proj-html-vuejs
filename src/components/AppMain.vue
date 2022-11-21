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
      <div class="service-section mt-5 g-5">
        <div class="left-side d-flex flex-wrap">
          <div class="card w-50 h-50">
            <div class="card-body">
              <h6 class="card-title">Graphic Design</h6>
              <small
                ><p class="card-text">
                  Have a passion for graphics and arts? Show your talents with
                  confidence and self-assertiveness.
                </p></small
              >
            </div>
            <img
              src="../assets/images/home-6-service-image-01.png"
              class="card-img-bottom"
              alt="..." />
          </div>
          <div class="card w-50 h-50">
            <div class="card-body">
              <h6 class="card-title">Graphic Design</h6>
              <small
                ><p class="card-text">
                  Have a passion for graphics and arts? Show your talents with
                  confidence and self-assertiveness.
                </p></small
              >
            </div>
            <img
              src="../assets/images/home-6-service-image-01.png"
              class="card-img-bottom"
              alt="..." />
          </div>
          <div class="card w-50 h-50 shadow g-3">
            <div class="card-body">
              <h6 class="card-title">Graphic Design</h6>
              <small
                ><p class="card-text">
                  Have a passion for graphics and arts? Show your talents with
                  confidence and self-assertiveness.
                </p></small
              >
            </div>
            <img
              src="../assets/images/home-6-service-image-01.png"
              class="card-img-bottom"
              alt="..." />
          </div>
          <div class="card w-50 h-50">
            <div class="card-body">
              <h6 class="card-title">Graphic Design</h6>
              <small
                ><p class="card-text">
                  Have a passion for graphics and arts? Show your talents with
                  confidence and self-assertiveness.
                </p></small
              >
            </div>
            <img
              src="../assets/images/home-6-service-image-01.png"
              class="card-img-bottom"
              alt="..." />
          </div>

          <!-- <div class="card">
            <div class="card-body">
              <h6 class="card-title">Graphic Design</h6>
              <small
                ><p class="card-text">
                  This is a wider card with supporting text below as a natural
                  lead-in to additional content. This content is a little bit
                  longer.
                </p></small
              >
            </div>
            <img
              src="../assets/images/home-6-service-image-01.png"
              class="card-img-bottom"
              alt="..." />
          </div> -->
          <!-- <div class="card">
            <div class="card-body">
              <h6 class="card-title">Graphic Design</h6>
              <small
                ><p class="card-text">
                  This is a wider card with supporting text below as a natural
                  lead-in to additional content. This content is a little bit
                  longer.
                </p></small
              >
            </div>
            <img
              src="../assets/images/home-6-service-image-01.png"
              class="card-img-bottom"
              alt="..." />
          </div> -->
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
    width: 50%;
    .card-text {
      font-size: xx-small;
    }
    .card-img-bottom {
      // width: 10rem;
      // padding-bottom: 5.6rem;
    }
  }
}
</style>
