<template>
  <div class="popularItems" @click="GoToPage()">
      <div class="flex pb-6 items-center">
      <div class="header">
          <img src="@/assets/images/crypto.jpg" class="sm: md:" alt="">
      </div>
      <div class="pr-2">
          <h1>بیت کوین برای سرمایه گذاری</h1>
          <div class="flex justify-between ">
              <p>آرمان کریمی</p>
              <p>2 بهمن</p>
          </div>
      </div>
  </div>
  
  </div>
</template>

<script>
export default {
    methods:{
        GoToPage(){
            this.$router.push('blog-post')
        }
    }
}
</script>

<style scoped>
.popularItems:hover{
    cursor: pointer;
}
.header > img{
    width: 100px;
    height: 75px;
    border-radius: 10px;
}

</style>