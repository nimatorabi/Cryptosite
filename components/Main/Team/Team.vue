<template>
  <div class="team-bg text-right" id="team">
    <div class="team container mx-auto">
      <div class="inline-flex content-between">
        <div
          class="imagesSec box-border"
          data-aos="fade-up"
          data-aos-duration="500"
          data-aos-ease="ease-in"
        >
          <img src="../../../assets/images/bitfinex.png" class="imgteam" />
        </div>
        <div
          class="teaminfo flex flex-col"
          data-aos="fade-up"
          data-aos-duration="750"
          data-aos-ease="ease-in"
        >
          <h2 class="pb-5 sm:justify-center p-8">متصل باش</h2>
          <p
            class="text-gray-600 sm:justify-center mx-auto p-8"
          >ما ابزارهای موبایل شما را ایجاد کردیم نیاز به تجارت در حرکت است.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.team {
  margin-top: 20px;
  margin-bottom: 20px;
}
.teamimg {
  max-height: 360px;
  margin-top: 50px;
}
.team-bg {
  background: url("../../../assets/images/bg-img/banner-02.png");
  max-height: 360px;
  margin-bottom: 150px;
}
.teaminfo {
  margin-top: 7rem;
}
h2 {
  font-size: 36px;
  color: white;
  font-weight: bold;
}
.imagesSec {
  position: relative;
  bottom: 10.7rem;
}
</style>
