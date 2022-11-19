<script>
export default {
  name: "AppHero",
};
</script>

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
            <li>
              Shop <i class="fa-solid fa-chevron-down"></i
              ><i class="fa-solid fa-cart-shopping"></i>
            </li>
            <li><i class="fa-regular fa-circle-user"></i></li>
            <li>
              <input type="search" placeholder="Search" /><span
                ><i class="fa-solid fa-magnifying-glass"></i
              ></span>
            </li>
          </ul>
        </div>
      </div>
      <div class="title-hero text-center text-white mt-3">
        <h2>Learn At Your Own Peace!</h2>
        <p>Get teamed up with the people oh the same will.</p>
        <button type="button" class="btn btn-success">
          Get started for free
        </button>
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
    position: relative;
    width: 80%;
    margin: 0 auto;
    align-items: center;
  }
  .menu-list {
    justify-content: space-around;
    display: flex;
    padding: 1rem;
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
    color: white;
  }
  .ul-list {
    margin-top: 0.3rem;
  }
  .fa-solid {
    font-size: xx-small;
    font-weight: xx-small;
  }
  .hero-image {
    width: 35rem;
    height: 17rem;
    margin: auto;
  }

  .left-person {
    width: 10rem;
    position: absolute;
    top: 21rem;
    left: -3rem;
  }
  .right-person {
    width: 7rem;
    position: absolute;
    top: 28rem;
    right: 0.7rem;
  }
}
</style>
