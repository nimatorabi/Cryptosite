<template>
  <div
    id="singleBlog"
    class="md:w-1/3 justify-center overflow-hidden"
    data-aos="fade-up"
    data-aos-duration="750"
    data-aos-ease="ease-in"
    data-aos-once="true"
  >
    <div class="blog-img" slot="blogimg">
      <a href="#">
        <img :src="imagesrc" alt class="video-ifram" />
      </a>
      <!-- <a href class="player">
        <play-icon class="custom-class"></play-icon>
      </a>-->
    </div>
    <div class="blog-title">
      <span class="text-sm">12 مهرماه 1399</span>
      <h3 class="mt-3 font-normal">
        <a href>IBM اثبات برای کار بلاکچین</a>
      </h3>
      <div class="blog-meta mt-3">
        <span class="ago text-sm text-gray-600">1 ساعت پیش</span>
      </div>
    </div>
  </div>
</template>

<script>
import { PlayIcon } from "vue-bytesize-icons";

export default {
  props: {
    imagesrc: {
      type: String,
      default: null
    }
  },
  components: { PlayIcon }
};
</script>

<style>
#singleBlog {
  padding: 15px;
  background: #ffffff;
  margin-bottom: 30px;
  max-width: 33.3333%;
  margin-left: 1rem;
  border-radius: 3px;
}
#singleBlog:hover {
  box-shadow: 0px 3px 5px 1px rgba(0, 0, 0, 0.144);
  transition: 0.5s ease-in-out;
  cursor: pointer;
}
#singleBlog .blog-img img {
  border-radius: 3px;
}
#singleBlog > a > img {
  max-width: 100%;
  height: auto;
}
#singleBlog > .blog-img:nth-child(2) #i-play {
  position: relative;
  left: 0 !important;
}
/* #singleBlog .share_options li {
  display: inline-block;
}
#singleBlog .share_options > li > a > img {
  vertical-align: middle;
}
#singleBlog .blog-img .player {
  box-sizing: border-box;
}
#singleBlog .blog-img .player .custom-class {
  position: relative;
  background: linear-gradient(to left, #f879b6 0%, #9982ed 100%);
  border-radius: 50%;
  top: -1rem;
  right: 19rem;
  color: white;
} */
#singleBlog .blog-img .player .custom-class:hover {
}

/* Responsive part */
@media only screen and (max-width: 445px) {
  #singleBlog {
    max-width: 100%;
    margin-left: 0;
  }
}
/*@media only screen and (max-width: 770px) and (min-width: 446px) {
  #singleBlog {
    max-width: 50%;
    margin: 0 auto;
    margin-left: 0;
  }
}*/
</style>
