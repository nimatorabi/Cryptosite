<template>
  <div id="header" class="overflow-hidden">
    <div class="container mx-auto">
      <div id="headerhome" class="inline-flex">
        <div class="intro-text sm:justify-centermd:block-flex">
          <h1 class>ارز دیجیتال،تکنولوژی برای کار.</h1>
          <p class="sm:p-4">برای پیشرفت در بیزینس خود از از دیجیتال ما استفاده کنید.</p>
          <div class="flex">
            <div class="btn_video">
              <a href>دریافت لیست مورد نظر</a>
            </div>
            <div class="video-wrapper">
              <div class="video-wrapper-btn">
                <span class="Presentation">
                  <a href="#">
                    <span></span>
                    <i></i>
                  </a>
                </span>
              </div>
            </div>
          </div>
        </div>
        <div class="intro-img pr-12 md:block-flex lg:inline-flex">
          <img src="../../assets/images/header-02.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { PlayIcon } from "vue-feather-icons";

export default {
  components: {
    PlayIcon
  }
};
</script>

<style>
#header {
  background: #ffffff;
  position: relative;
  min-height: 820px;
  z-index: 99;
}
#header:before {
  position: absolute;
  background: url("../../assets/images/bg-img/banner-02.png") no-repeat 100%
    100%;
  background-size: cover;
  content: "";
  height: 100%;
  width: 100%;
  left: 0;
  top: 0;
  z-index: -2;
}
#header .intro-text {
  margin-top: 140px;
  padding: 0 110px 0 0;
}
#header .intro-text h1 {
  font-size: 40px;
  font-weight: 600;
  line-height: 55px;
  color: #ffffff;
}
#header .intro-text p {
  font-size: 18px;
  line-height: 30px;
  margin-top: 30px;
  font-weight: 400;
  padding-right: 0px;
  color: #a2b2ff;
}
#header .intro-text .btn_video {
  display: flex;
  margin-top: 40px;
}
#header .intro-text .btn_video a {
  background: #ffffff;
  color: #562ad8;
  text-transform: capitalize;
  font-size: 18px;
  padding: 10px 30px;
  margin-top: 0px;
  margin-right: 50px;
  border-radius: 50px;
  vertical-align: middle;
  margin-right: 0;
}
#header .intro-text .btn_video a:hover {
  background: #00e9fe;
  color: #ffffff;
}
#header .intro-img {
  margin-top: 0px;
  margin-right: 4%;
}
#header .intro-img img {
  height: auto;
  width: auto;
  margin-left: -6%;
  margin-top: 5%;
}
/*.Presentation {
  color: white;
  right: 5rem;
  position: relative;
}
.custom-class {
  background: white;
  color: turquoise !important;
  border-radius: 50%;
  margin-top: 2rem;
  padding: 25px;
}*/
</style>
