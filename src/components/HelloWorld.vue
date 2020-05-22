<template>
<div class="container">
  <div class="section">



    <div class="col span_3_of_12" id="snail">
    </div>
    <div class="col span_6_of_12" id="about">
      <div class="border"></div>
      <h3>Anders K. Engsted's Portfolio</h3>
      <ul></ul>
      <ul></ul>
      <h2>operator @ hyoscine.org</h2>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/iZmEQyofoEo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="col span_3_of_12" id="snail">
</div>

    </div>

  </div>

</template>

<script>
export default {
  name: 'Projects',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="css">

  .container {
    /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#000000+91,ffffff+100&1+32,0.4+89,0+100 */
    background: -moz-linear-gradient(top,  rgba(0,0,0,1) 32%, rgba(0,0,0,0.4) 89%, rgba(0,0,0,0.33) 91%, rgba(255,255,255,0) 100%); /* FF3.6-15 */
    background: -webkit-linear-gradient(top,  rgba(0,0,0,1) 32%,rgba(0,0,0,0.4) 89%,rgba(0,0,0,0.33) 91%,rgba(255,255,255,0) 100%); /* Chrome10-25,Safari5.1-6 */
    background: linear-gradient(to bottom,  rgba(0,0,0,1) 32%,rgba(0,0,0,0.4) 89%,rgba(0,0,0,0.33) 91%,rgba(255,255,255,0) 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#000000', endColorstr='#00ffffff',GradientType=0 ); /* IE6-9 */


  }



.section {
  max-width: 100%;
  margin-top: 2%;
  padding: 0.2%;
  margin-left: 2%;
  margin-right: 2%;
  height: 83vh;
  width: auto;

  display: flex;
  text-align: center;


}

h2 {
  color: skyblue;
}

ul {
  text-align: center;
}

  img {
    max-width:100%;
    max-height:auto%;
  }

  iframe {
    max-width: 100%;
    max-height: auto;
  }

  h3 {
    color: darkorange;
    font-family: sans-serif;
  }


</style>

<style scoped>


  /*  SECTIONS  */
  .section {
    clear: both;
    padding: 0px;
    margin: 0px;
    text-align: center;
   /* background: linear-gradient(to bottom, rgba(url('../assets/21.jpg'), 0.0), rgba(url('../assets/21.jpg'), 1.0));

    */

  }

  /*  COLUMN SETUP  */
  .col {
    display: block;
    float:left;
    margin: 1% 0 1% .5%;
  }
  .col:first-child { margin-left: 0; }

  /*  GROUPING  */
  .group:before,
  .group:after { content:""; display:table; }
  .group:after { clear:both;}
  .group { zoom:1; /* For IE 6/7 */ }

  /*  GRID OF TWELVE  */
  .span_12_of_12 {
    width: 100%;
  }

  .span_11_of_12 {
    width: 91.62%;
  }
  .span_10_of_12 {
    width: 83.25%;
  }

  .span_9_of_12 {
    width: 74.87%;
  }

  .span_8_of_12 {
    width: 66.5%;
  }

  .span_7_of_12 {
    width: 58.12%;
  }

  .span_6_of_12 {
    width: 49.75%;
  }

  .span_5_of_12 {
    width: 41.37%;
  }

  .span_4_of_12 {
    width: 33%;
  }

  .span_3_of_12 {
    width: 24.62%;
  }

  .span_2_of_12 {
    width: 16.25%;
  }

  .span_1_of_12 {
    width: 7.875%;
  }

  /*  GO FULL WIDTH BELOW 480 PIXELS */
  @media only screen and (max-width: 480px) {
    .col {  margin: 1% 0 1% 0%; }

    .span_1_of_12, .span_2_of_12, .span_3_of_12, .span_4_of_12, .span_5_of_12, .span_6_of_12, .span_7_of_12, .span_8_of_12, .span_9_of_12, .span_10_of_12, .span_11_of_12, .span_12_of_12 {
      width: 100%;
      align-content: center;
    }
  }

</style>

