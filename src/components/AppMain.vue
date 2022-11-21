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
          <div class="box-first">
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
          <div class="box-third">
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
          <div class="right-title">
            <p>TOGETHER WE CAN CREATE</p>
            <h4>Services We Can Provide For Our Clients</h4>
            <span
              ><small
                ><p class="font-services">
                  <i class="fa-solid fa-check"></i> Select & costumise courses
                  and preferences.
                </p></small
              ></span
            >
            <span class="font-services"
              ><p>
                <i class="fa-solid fa-check"></i> Select & costumise courses and
                preferences.
              </p></span
            >
            <span
              ><p class="font-services">
                <i class="fa-solid fa-check"></i> Select & costumise courses and
                preferences.
              </p></span
            >
            <span
              ><p class="font-services">
                <i class="fa-solid fa-check"></i> Select & costumise courses and
                preferences.
              </p></span
            >
            <button type="button" class="btn btn-success">
              Get started for free
            </button>
          </div>
        </div>
      </div>
      <div class="features-section">
        <div class="text-center">
          <small><h6 class="h6">CHOSE A COURSE TO GET STARTED</h6></small>
          <h4>Latest Featured Courses</h4>
        </div>
        <div class="courses">
          <img
            class="b-radius"
            src="../assets/images/course-02-480x298.jpg"
            alt="" />
          <div class="courses__price">
            <h5>
              $40.<small><span>00</span></small>
            </h5>
            <h6>Learning to Write a Professional <br />Author</h6>
            <span
              ><i class="fa-regular fa-file-lines"></i> 20 Lessons
              <i class="fa-regular fa-user"></i> 50 Students
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
img {
  width: 100%;
}
.h6 {
  font-size: xx-small;
}
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

    .box-first,
    .box-second,
    .box-third,
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
        position: absolute;
        top: 55%;
        right: 0%;
      }
      .box-third {
        top: 45%;
        right: 0%;
        position: absolute;
      }
    }
  }
}
// FEAUTER-SECTION
.right-title {
  text-align: start;
  padding-top: 8rem;
  width: 50%;
  color: rgb(29, 141, 104);
}
.font-services {
  font-size: xx-small;
}
.b-radius {
  width: 6rem;
  height: 6rem;
  border-radius: 50%;
  object-fit: cover;
}
</style>
