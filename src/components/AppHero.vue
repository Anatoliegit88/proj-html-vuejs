<script>
export default {
  name: "AppHero",
};
</script>
<!-- HERO -->
<template>
  <div class="container-hero">
    <div class="small-container">
      <div class="menu-list">
        <span>
          <img class="logo" src="../assets/images/light-logo.png" alt="" />
        </span>
        <div class="ul-list">
          <ul>
            <li>Home <i class="fa-solid fa-chevron-down"></i></li>
            <li>Pages <i class="fa-solid fa-chevron-down"></i></li>
            <li>Courses <i class="fa-solid fa-chevron-down"></i></li>
            <li>Features <i class="fa-solid fa-chevron-down"></i></li>
            <li>Blog <i class="fa-solid fa-chevron-down"></i></li>
            <li>Shop <i class="fa-solid fa-chevron-down"></i></li>
            <li><i class="fa-solid fa-cart-shopping"></i></li>
            <li><i class="fa-regular fa-circle-user"></i></li>
            <li>
              <input
                class="input p-1 rounded"
                type="search"
                placeholder="Search" />
              <img
                class="search"
                src="https://img.icons8.com/external-kiranshastry-gradient-kiranshastry/64/null/external-search-alignment-and-tools-kiranshastry-gradient-kiranshastry.png" />
            </li>
            <li>
              <img
                class="circle"
                src="https://img.icons8.com/windows/32/null/0-circle.png" />
            </li>
          </ul>
        </div>
      </div>
      <div class="title-hero text-center text-white mt-3">
        <h2>Learn At Your Own Peace!</h2>
        <small
          ><h6 class="sub-text">
            Get teamed up with the people oh the same will.
          </h6></small
        >
        <button type="button" class="btn btn-success mt-3">
          Get started for free
        </button>
        <div class="extra">
          <img
            src="https://img.icons8.com/external-kmg-design-basic-outline-kmg-design/32/null/external-ruler-back-to-school-kmg-design-basic-outline-kmg-design-2.png" />
          <img
            src="https://img.icons8.com/fluency-systems-regular/32/null/safety-float-1.png" />

          <img src="https://img.icons8.com/sf-regular/32/null/book.png" />
          <img
            src="https://img.icons8.com/sf-regular/48/null/shopping-cart.png" />
        </div>
      </div>
      <div class="text-center mt-5">
        <img
          class="hero-image rounded border border-5"
          src="../assets/images/home-6-hero-poster-final.jpg"
          alt="" />
      </div>
      <img
        class="left-person"
        src="../assets/images/home-6-hero-left-person-244x300.png"
        alt="" />
      <img
        class="right-person"
        src="../assets/images/home-6-hero-right-person-195x300.png"
        alt="" />
      <img
        class="you-tube"
        src="../assets/images/icon-youtube-play.png"
        alt="" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
img {
  width: 100%;
}
.logo {
  width: 7rem;
}
.container-hero {
  width: 100%;
  background-color: rgb(21, 0, 70);
  height: 30rem;

  .small-container {
    width: 80%;
    margin: 0 auto;
    align-items: center;
  }
  .menu-list {
    justify-content: space-around;
    display: flex;
    padding: 1rem;
  }
  .search {
    width: 0.7rem;
    position: absolute;
    left: 81%;
    top: 6.3%;
  }
  .circle {
    position: absolute;
    left: 68%;
    top: 5.3%;
    background-color: white;
    width: 0.6rem;
    border-radius: 50%;
  }

  ul {
    align-items: center;
    vertical-align: middle;
    display: flex;
    justify-content: center;
  }
  li {
    list-style: none;
    font-weight: 600;
    font-size: xx-small;
    padding: 0.2rem;
    padding-left: 0.6rem;
    color: white;
  }
  .ul-list {
    margin-top: 0.3rem;
  }
  .fa-solid {
    font-size: xx-small;
    font-weight: xx-small;
  }
  .sub-text {
    color: rgb(162, 162, 162);
    font-size: x-small;
  }
  .hero-image {
    position: relative;
    width: 32rem;
    height: 17rem;
    margin: auto;
    z-index: 10;
  }

  .left-person {
    width: 10rem;
    position: absolute;
    top: 21rem;
    left: 6.5rem;
    // z-index: -1;
  }
  .right-person {
    width: 7rem;
    position: absolute;
    top: 28rem;
    right: 8.5rem;
  }
  .you-tube {
    position: absolute;
    top: 80%;
    left: 50%;
    width: 3.5rem;
    z-index: 11;
  }
  .extra {
    width: 1.1rem;
    position: absolute;
    top: 20%;
    right: 0;
    border: 1px solid gainsboro;
    border-top-left-radius: 0.3rem;
    border-bottom-left-radius: 0.3rem;
    background-color: white;
  }
}
</style>
