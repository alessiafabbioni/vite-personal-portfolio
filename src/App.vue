<script>
//import HelloWorld from './components/HelloWorld.vue'
import AppHeader from './components/AppHeader.vue';
import AboutMe from './components/AboutMe.vue';
import MySkills from './components/MySkills.vue';
import MyProjects from './components/MyProjects.vue';
import MyContact from './components/MyContact.vue';

//import axios
import axios from 'axios';

export default {
  components: {
    AppHeader,
    AboutMe, 
    MySkills,
    MyProjects,
    MyContact,
  }
}

</script>

<template>
  <AppHeader/>
  <main>
    <AboutMe/>
    <MySkills/>
    <MyProjects/>
    <MyContact/>
  </main>

</template>

<style lang="scss">
@use './styles/general.scss';

</style>
