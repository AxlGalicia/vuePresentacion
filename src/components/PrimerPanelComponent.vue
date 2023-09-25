<template>
<div class="columns">
  <div class="column FondoColorColumna1">
    <DescripcionComponent></DescripcionComponent>
  </div>
  <div class="column FondoColorColumna2 ">
    <!--<img src="../assets/earth.jpg" >-->
    <figure class="image">
        <img src="../assets/earth.jpg" class="imagen">
    </figure>
  </div>

</div>
</template>

<script setup>
import DescripcionComponent from './DescripcionComponent.vue';


</script>

<style scoped>

.FondoColorColumna1
{

    /*background-color: aquamarine;*/
    display: grid;
    align-content: center;
    text-align: center;

}

.FondoColorColumna2
{

    /*background-color: rgb(236, 127, 255);*/
    padding: 30px;

}

img{
    /*border: 10px solid transparent;
    border-image: linear-gradient(to right, red, purple) 1;*/
    border-radius:50%;
    /*box-shadow: 0px 0px 10px 10px #ec731e; */
    box-shadow: 0px 0px 10px 10px #0CF556;
}


</style>