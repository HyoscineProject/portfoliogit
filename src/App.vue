


<template>

  <div id="app">
   <Navigation/>
      <HelloWorld/>
    <Projects/>
    <Footer/>
  </div>
</template>

<script>
  import Projects from "@/components/Projects";
  import HelloWorld from "@/components/HelloWorld";
  import Navigation from "@/components/Navigation";
  import Footer from "@/components/Footer";


export default {
  name: 'App',
  components: {

    Projects,
    HelloWorld,
    Navigation,
    Footer,
  }
}

</script>

<style lang="css">
    body {
        margin:0;
        background-image: url("assets/background.jpg");
        background-repeat: no-repeat;
        background-color: black;
        background-position-y: 1%;
        background-size: 100%;

   }
    #app {
        background: inherit;
        backdrop-filter: blur(50px);
        background-blend-mode: difference;
        background-size: 100%;



    }

    li {
        list-style: georgian;

    }


 </style>