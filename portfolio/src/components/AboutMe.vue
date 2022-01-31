<template>
  <main>
  
<div class="container">
<div class="up">
<div class="me">Beloved Me
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde minus aspernatur tempore quo cumque dolor porro soluta, nesciunt ipsum! Incidunt iusto provident doloribus saepe magni. Distinctio mollitia possimus ipsam soluta?</p>
</div>
</div>
<div class="down">
<div class="why">
why i become full-stack developer 
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos enim voluptates accusamus consectetur ab aut eum amet, itaque eius maiores saepe aliquam quia possimus molestiae, ad, expedita tenetur laudantium eveniet.</p>
</div>
</div>
</div>
  </main>
</template>

<script>
export default {
name:"AboutMe"

}
</script>

<style scoped>
.container,.up,.down{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.me,.why{
    display: flex;
    justify-content: space-around;
}
p{
    padding-left: 250px;
}


</style>