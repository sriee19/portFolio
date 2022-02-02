<template>
  <main>
    <h2>EXPERIENCE</h2>
    <div class="container">
      <div class="up">
        <div class="left">
        <h3>december2021-january2022</h3>
        </div>
        <div class="right"><span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis repudiandae sapiente doloribus ea voluptatum quia!</span></div>
      </div>
      <div class="down">
        <div class="left1">
        <h3>january2022-present</h3>
        </div>
        <div class="right1"><span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime nam maiores facere cumque ducimus exercitationem?</span></div>
      </div>
    </div>
    <h2>DIPLOMES</h2>
    <div class="container">
      <div class="up">
        <div class="left">
        <h3>SONA COLLEGE OF TECHNOLOGY</h3>
        </div>
        <div class="right"><span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis repudiandae sapiente doloribus ea voluptatum quia!</span></div>
      </div>
      <div class="down">
        <div class="left1">
        <h3>INTERNEZY</h3>
        </div>
        <div class="right1"><span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime nam maiores facere cumque ducimus exercitationem?</span></div>
      </div>
      <div class="up1">
      <div class="left2">
      <h3>SENIOR SECONDARY</h3>
      </div>
      <div class="right2">
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque corrupti nemo dolore mollitia necessitatibus enim?</span>
      </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "MyWork",
};
</script>

<style scoped>
h2 {
  text-align: center;
  
}
.container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}
.up,.down,.up1{
    display: flex;
    justify-content: space-evenly;
    margin-top: 25px;
}
.right,.right1,.right2{
    padding-left: 30px;
}
</style>