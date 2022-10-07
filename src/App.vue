<template>
  <div id="app">
    <HeaderComponent :links="menu"/>
    <Section1Content />
    <Section2Content />
    <Section3Content />
    <Section4Content />
    <Section5Content />
    <Section6Content />
    <FooterComponent />
  </div>
  
  
  

  
</template>


<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";
import Section1Content from "./components/Section-1-Content.vue";
import Section2Content from "./components/Section-2-content.vue";
import Section3Content from "./components/Section-3-content.vue";
import Section4Content from "./components/Section-4-content.vue";
import Section5Content from "./components/Section-5-content.vue";
import Section6Content from "./components/Section-6-content.vue";






export default {
    components: {
    HeaderComponent,
    FooterComponent,
    Section1Content,
    Section2Content,
    Section3Content,
    Section4Content,
    Section5Content,
    Section6Content
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
  overflow-x: hidden;
  box-sizing: border-box;
  margin: 0px;
  padding: 0px;

}

*h5{
  overflow: hidden;
}
</style>
