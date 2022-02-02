<template>
  <main>
  <h2>MY PROJECTS</h2>
  <div class="container">
  <div class="images">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTFwqMA3aeJ2qwDViOx008ccdLgd1hm-3K2sg&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSgVwBNvSKdhJjmQq-YjSD2auV4PisMPgy-pg&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTTRzHwjj_w4g5jtbmXbcDdP9pzVc6e_y6f6g&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_LPKjhDlWOOuuda8SnHUDx5wTNmEXoB79Jg&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQsN_kvxDVldkXu4Xya2-4YZW_uIncGQskZg&usqp=CAU" alt="">
  </div>
  </div>
  </main>
</template>

<script>
export default {
name:"RecentProject"
}
</script>

<style lang="scss" scoped >
.container{
  display: flex;
  justify-content: space-evenly;
}
.images{
    img{
      height: 250px;
      width: 250px;
    }
}
h2{
  text-align: center;
}
</style>