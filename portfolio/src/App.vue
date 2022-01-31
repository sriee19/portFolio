<template>
<v-app>
<hello-world/>
<about-me/>
<my-work/>
</v-app>
</template>

<script>
import AboutMe from './components/AboutMe.vue'
import HelloWorld from './components/HelloWorld.vue'
import MyWork from './components/MyWork.vue'
export default {
  components: { HelloWorld, AboutMe, MyWork },

}
</script>

<style>

</style>