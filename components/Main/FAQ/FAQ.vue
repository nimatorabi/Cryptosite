<template>
  <div class="faq text-justify p-8 overflow-hidden" id="faqsec">
    <div class="container mx-auto">
      <div class="sm:block-inline md:inline-flex">
        <div class="sm:w-full text-center px-8 md:w-1/2">
          <img
            data-aos="fade-up"
            data-aos-duration="750"
            data-aos-ease="ease-in"
            src="../../../assets/images/faq-02.png"
            alt
            class
          />
          <h2
            data-aos="fade-up"
            data-aos-duration="750"
            data-aos-ease="ease-in"
            class="text-xl text-right font-bold"
          >سوالات متداول</h2>
          <p
            class="text-gray-500 mt-5 ml-5"
            data-aos="fade-up"
            data-aos-duration="750"
            data-aos-ease="ease-in"
          >
            دستیار NRM مصنوعی مبتنی بر شبکه عصبی ، فوراً استفاده از داده های
            کاربر را تجزیه و تحلیل می کند.
          </p>
        </div>
        <div class>
          <vs-collapse
            type="margin"
            data-aos="fade-up"
            data-aos-duration="1350"
            data-aos-ease="ease-in"
          >
            <vs-collapse-item>
              <div
                slot="header"
                class="w-10/12 leading-8"
              >از چه ارزهای رمزپایه ای می توان برای خرید استفاده کرد؟</div>هوش مصنوعی مبتنی بر شبکه های عصبی ، با استفاده از جدیدترین
              الگوریتم های یادگیری خود ، تجزیه و تحلیل و مقایسه نورون هایی که در
              آنها اصلاح می شوند ، بر اساس تاریخ ساخته شده است.
            </vs-collapse-item>
            <vs-collapse-item>
              <div slot="header" class="w-10/12 leading-8">چگونه میتوانم از این سایت استفاده کنم؟</div>هوش مصنوعی مبتنی بر شبکه های عصبی ، با استفاده از جدیدترین
              الگوریتم های یادگیری خود ، تجزیه و تحلیل و مقایسه نورون هایی که در
              آنها اصلاح می شوند ، بر اساس تاریخ ساخته شده است.
            </vs-collapse-item>
            <vs-collapse-item>
              <div slot="header" class="w-10/12 leading-8">برای بهره بری بهتر از ما پشتیبان بگیرید</div>هوش مصنوعی مبتنی بر شبکه های عصبی ، با استفاده از جدیدترین
              الگوریتم های یادگیری خود ، تجزیه و تحلیل و مقایسه نورون هایی که در
              آنها اصلاح می شوند ، بر اساس تاریخ ساخته شده است.
            </vs-collapse-item>
            <vs-collapse-item>
              <div slot="header" class="w-10/12 leading-8">بهترین سایت در زمینه ارز دیجیتال</div>هوش مصنوعی مبتنی بر شبکه های عصبی ، با استفاده از جدیدترین
              الگوریتم های یادگیری خود ، تجزیه و تحلیل و مقایسه نورون هایی که در
              آنها اصلاح می شوند ، بر اساس تاریخ ساخته شده است.
            </vs-collapse-item>
          </vs-collapse>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.faq {
  background: #f5f5f7 !important;
  padding: 100px 0 150px !important;
}
.faq p {
  color: #7a839e;
  font-size: 16px;
}
.con-radios-example {
  display: flex;
  justify-content: flex-end;
  flex-direction: column;
  align-items: flex-start;
  padding-bottom: 5px;
}
.con-vs-radio {
  margin: 5px;
}
.icon-header .vs-collapse-item--icon-header {
  box-sizing: border-box;
}
.vuesax-app-is-ltr .vs-collapse-item--icon-header {
  /*
  make responsive horizentall scroll error...
  left: 35px;*/
  position: absolute;
  left: 35px;
  color: #12ddd0;
  font-weight: 600;
  font-size: 14px;
  padding-right: 0;
  transition: 0.5s ease-in-out;
}
.con-content--item {
  font-size: 16px;
  color: #7a839e;
  margin: 0;
}
.vs-collapse-item--header {
  line-height: 80px;
  color: #19233b;
  font-size: 22px;
  font-weight: 400;
}
.faq h2 {
  font-size: 36px;
  margin-bottom: 15px;
  color: black;
}
.vs-collapse.margin .vs-collapse-item {
  background: #ffffff !important;
  padding-right: 1rem;
}
</style>
