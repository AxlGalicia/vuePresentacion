<template>
    <div class="contenedor">
        <div class="caja columns" id="contacto">
            <div class="column">
                <div class="contactoTitulo">
                    Información de contacto
                </div>
                <div class="contactoDescripcion">
                    En este apartado puede encontrar los medios para comunicarse conmigo.
                </div>
            </div>

            <div class="column">
                <div class="contactoLink">
                    <ul>
                    <li>Número de teléfono: <strong>(+502) 54451284</strong></li>
                    <li>Correo electrónico: <strong class="arregloDesbordamiento">axlgreatga@gmail.com</strong></li>
                    <li>Linkedln: <strong class="arregloDesbordamiento">https://www.linkedin.com/in/axl-galicia-b650b2249/</strong></li>
                </ul>
                </div>
            </div>



        </div>
    </div>

    <div class="notification is-link">
        Esta página se seguirá actualizando con el tiempo, ya que estaré aprendiendo y reforzando mis conocimientos. Gracias por visitar esta página de presentación.
    </div>
    
</template>

<script setup>

</script>

<style scoped>
    .contenedor{
        /*background-color: aliceblue;*/
        padding-top: 20px;
        padding-bottom: 20px;
        margin-top: 20px;
        margin-bottom: 20px;
    }

    .caja{
        /*background-color: rgb(232, 236, 236);*/
        /*background-color: rgb(133, 239, 198);*/
        /*background: linear-gradient(rgb(118, 118, 236), rgb(249, 125, 145));*/
        /*background: linear-gradient(to right,rgb(151, 242, 215), rgb(118, 118, 236));*/
        background: linear-gradient(to right,rgb(151, 242, 215), rgb(226, 95, 250));
        border-radius: 20px;
        box-shadow: 0px 0px 25px black;
        padding: 20px;
        margin-left: 11.5%;
        margin-right: 11.5%;

    }

    .contactoTitulo{
        color: black;
        font-size: xx-large;
        font-family: 'Arvo', serif;
        font-style: bold;
        font-weight: 700;
        text-align: center;

    }

    .contactoDescripcion{
        color: rgb(92, 88, 88);
        font-size: x-large;
        font-family: 'Arvo', serif;
        font-style: bold;
        font-weight: 400;
        text-align: center;
    }

    .contactoLink{
        justify-content: center;
        text-align: center;
        padding: 5%;
        font-size: larger;
        font-family: 'Arvo', serif;
        font-style: bold;
        font-weight: 500;
    }

    .arregloDesbordamiento{
        overflow-wrap: break-word;
    }

    @media only screen and (max-width: 768px){

        .caja{
        /*background-color: rgb(232, 236, 236);*/
        /*background-color: rgb(133, 239, 198);*/
        /*background: linear-gradient(rgb(118, 118, 236), rgb(249, 125, 145));*/
        /*background: linear-gradient(to right,rgb(151, 242, 215), rgb(118, 118, 236));*/
        background: linear-gradient(to right,rgb(151, 242, 215), rgb(226, 95, 250));
        border-radius: 20px;
        box-shadow: 0px 0px 25px black;
        padding: 20px;
        margin-left: 7%;
        margin-right: 7%;

    }


    }



</style>