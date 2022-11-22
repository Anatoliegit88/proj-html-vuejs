<script>
export default {
  name: "AppFooter",
  props: {
    leftList: Array,
  },
  data() {
    return {};
  },
};
</script>

<template>
  <footer class="footer">
    <div class="footer-left">
      <ul class="left-list">
        <!-- <h6>Address</h6> -->

        <li class="list" v-for="(list, index) in leftList">
          <p :class="list">382191St # 87394 Miami, FL 33179-3899</p>
        </li>

        <li>+1(305) 547-9909 (9am-5pm EST,Monday-Friday)</li>
        <li>support@maxcouch.com</li>
        <li>
          <span class="social"
            ><i class="fa-brands fa-square-facebook"></i
          ></span>
          <span class="social"><i class="fa-brands fa-twitter"></i></span>
          <span class="social"
            ><i class="fa-brands fa-square-instagram"></i
          ></span>
          <span class="social"><i class="fa-brands fa-linkedin"></i></span>
        </li>
      </ul>
    </div>
    <div class="footer-right">
      <div>
        <ul>
          <h6>Explore</h6>
          <li>Start here</li>
          <li>Blog</li>
          <li>About us</li>
        </ul>
      </div>
      <div>
        <ul>
          <br /><br />
          <li>Success story</li>
          <li>Courses</li>
          <li>Contact us</li>
        </ul>
      </div>
      <div>
        <ul>
          <h6>Information</h6>
          <li>Membership</li>
          <li>Purchase guide</li>
          <li>Privacy policy</li>
          <li>Terms of services</li>
        </ul>
      </div>
    </div>
  </footer>
  <div class="text-center">
    <small
      ><p>
        <i class="fa-regular fa-copyright"></i>2020 Maxcouch. All Rights
        Reserved.
      </p></small
    >
  </div>
</template>

<style lang="scss" scoped>
.footer {
  width: 100%;
  display: flex;
  justify-content: space-around;
  background-color: rgb(244, 242, 242);
}
.footer-left {
  width: 50%;
  padding: 3rem;
  padding-left: 10rem;
}
.footer-right {
  display: flex;
  width: 50%;
  padding: 3rem;
  padding-right: 10rem;
  justify-content: space-around;
}
.text-center {
  background-color: rgb(244, 242, 242);
  padding: 1rem;
}
ul {
  font-size: xx-small;
  list-style: none;

  .social {
    margin-right: 0.5rem;
  }
}
</style>
