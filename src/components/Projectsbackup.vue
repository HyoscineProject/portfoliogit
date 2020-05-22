<template>
    <div class="section">

            <div class="container">
                <div class="col_span_12_of_12" id="gradient"></div>
                <!--
                <div class="col span_3_of_12">
                                    <div class="box">
                        <img src="../assets/21.jpg">
                        <span>CSS</span>
                    </div>
                </div>
                <div class="col span_3_of_12">
                    <div class="box">
                        <img src="../assets/jj.jpg">
                        <span>CSS</span>
                    </div>
                </div>
                <div class="col span_3_of_12">
                    <div class="box">
                        <img src="../assets/retrospace.jpg">
                        <span>CSS</span>
                    </div>
                </div>
                <div class="col span_3_of_12">
                    <div class="box">
                        <img src="../assets/sphinx.jpg">
                        <span>CSS</span>
                    </div>
                </div>
                -->


                </div>


            </div>




    </div>

</template>

<script>
    export default {
        name: "Projects"
    }
</script>

<style scoped>

    .container {
        display: flex;
        width: 100%;
        padding: 2% 2%;
        box-sizing: border-box;
        height: 40vh;

    }

    .box {
        flex: 1;
        overflow: hidden;
        transition: .5s;
        margin: 0 2%;
        box-shadow: 0 20px 30px rgba(0,0,0,.1);
        line-height: 0;
        height: 45vh;

    }

    .box > img {
        width: 200%;

        height: calc(100% - 10vh);
        object-fit: cover;
        transition: .5s;
    }

    .box > span {
        font-size: 3.8vh;
        display: block;
        text-align: center;
        height: 10vh;
        line-height: 2.6;
    }

    .box:hover { flex: 1 1 50%;
        height: 95vh;
    width: 90%;
    }
    .box:hover > img {
        width: 100%;
        height: 100%;
        overflow: scroll;
    }

    span {
        color: lightsalmon;
    }
</style>

<style scoped>


    #gradient   {
        /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#aa33bf+0,ffffff+100&1+0,0+100 */
        background: -moz-radial-gradient(center, ellipse cover,  rgba(170,51,191,1) 0%, rgba(255,255,255,0) 100%); /* FF3.6-15 */
        background: -webkit-radial-gradient(center, ellipse cover,  rgba(170,51,191,1) 0%,rgba(255,255,255,0) 100%); /* Chrome10-25,Safari5.1-6 */
        background: radial-gradient(ellipse at center,  rgba(170,51,191,1) 0%,rgba(255,255,255,0) 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
        filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#aa33bf', endColorstr='#00ffffff',GradientType=1 ); /* IE6-9 fallback on horizontal gradient */

    }

    /*  SECTIONS  */
    .section {
        clear: both;
        padding: 0px;
        margin: 0px;
        text-align: center;
        background-color: rgba(0,0,0,1) 100%);



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

