<template>
  <div id="app">
    <HeaderComponent :links="menu"/>
    <FooterComponent />
  </div>
  
  
  

  
</template>


<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";






export default {
    components: {
    HeaderComponent,
    FooterComponent
},
    data(){
      return {
        menu: [
          {
              text: "HOME",
              url: "#",
              current: false,
          },
          {
              text: "ABOUT",
              url: "#",
              current: false,
          },
          {
              text: "SERVICE",
              url: "#",
              current: false,
          },
          {
              text: "SHOWCASE",
              url: "#",
              current: false,
          },
          {
              text: "BLOG",
              url: "#",
              current: false,
          },
          {
              text: "CONTACT",
              url: "#",
              current: false,
          },
        ]
      }
    }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
*{
  overflow: hidden;

}
</style>
