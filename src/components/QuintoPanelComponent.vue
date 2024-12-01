<template>
    <div class="panelExperiencia">

        <div class="card contenedor">
            <div class="card-content">
                <p class="title title-extra">
                Experiencia valiosa
                </p>
                <div class="columns">
                    <div class="column imagen">
                        <figure class="image ">
                            <img src="../assets/logo_neonet.png" class="imagen">
                         </figure>
                    </div>
                    <div class="column">
                        <div class="fuenteDescripcion">
                            A lo largo del año 2024 trabajando en NeoNet mis habilidades se han diversificado y reforzado las cuales son:
                        </div>
                        <div class="listado fuenteDescripcion">
                        <ul class="" type="square">
                        <li>
                    Conocimiento técnico en pasarelas de pago
                        </li>
                        <li>
                    Funcionamiento de dispositivos de pago
                        </li>
                        <li>
                    Arquitecturas de software
                        </li>
                        <li>
                    Comprensión de la infraestructura en el proceso de pagos electronicos
                        </li>
                        <li>
                    Integración de comercios hacias las pasarelas de pago
                        </li>
                        </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>

</template>

<script setup>


</script>

<style scoped>

    .panelExperiencia {

        padding: 40px;
    /*0background: rgb(250,163,91);*/

    }

    .contenedor{
        /*background: linear-gradient(to right,rgb(207, 208, 208), rgb(152, 245, 228));*/
        /*background: rgb(242,241,247);
        background: linear-gradient(90deg, rgba(242,241,247,1) 0%, rgba(180,223,220,1) 46%, rgba(137,217,233,1) 100%);*/
        /* background: rgb(49,84,196);
        background: linear-gradient(90deg, rgba(49,84,196,1) 0%, rgba(141,54,247,1) 42%, rgba(255,239,0,1) 100%); */
        /* background: rgb(166,146,190);
        background: linear-gradient(90deg, rgba(166,146,190,1) 0%, rgba(133,38,247,1) 49%, rgba(224,237,53,1) 100%); */
        /* background: rgb(137,217,233);
        background: linear-gradient(90deg, rgba(137,217,233,1) 0%, rgba(133,38,247,1) 49%, rgba(166,146,190,1) 100%); */
        /* background: rgb(213,248,255);
        background: linear-gradient(90deg, rgba(213,248,255,1) 45%, rgba(133,38,247,1) 69%, rgba(166,146,190,1) 100%); */
        background: linear-gradient(to right,rgb(151, 242, 215), rgb(226, 95, 250));
        border-radius: 20px;
        box-shadow: 0px 0px 25px rgb(77, 65, 65);
        min-height: 200px;
    }

    .title-extra{
        text-align: center;
        color: rgb(0, 0, 0);
    }

    .leaf {
        --size: 200px;
        --gradient: linear-gradient(limegreen, darkgreen);

        background: var(--gradient);
        width: var(--size);
        height: var(--size);
        border-radius: 50% 0 50% 0;
    }

    .splash{

        width: 100px;
        height: 100px;
        background:radial-gradient(circle at top left,#fff 5%, transparent 50%), radial-gradient(circle at bottom right, #fff 5%, transparent 50%);
        mask: radial-gradient(circle at center,white 50%, transparent 50%);
        transform: rotate(45deg);

    }

    ul{
        list-style-type: square;
    }

    .listado{
        padding-left: 20%;
        padding-top: 10px;
        text-align: left;
        padding-bottom: 10px;
    }

    .fuenteDescripcion{

        color: rgb(92, 88, 88);
        font-size: large;
        font-family: 'Arvo', serif;
        font-style: bold;
        font-weight: 400;
    }

    .imagen{

        /*padding: auto;*/
        text-align: center;
        padding-top: 5%;
    }

    @media only screen and (min-width: 1320px){

        .panelExperiencia {

            padding-top: 60px;
            /*0background: rgb(250,163,91);*/

        }

        .contenedor{
        background: linear-gradient(to right,rgb(151, 242, 215), rgb(226, 95, 250));
        border-radius: 20px;
        box-shadow: 0px 0px 25px rgb(77, 65, 65);
        min-height: 200px;
        margin-left: 10%;
        margin-right: 10%;
    }

        .title-extra{
        text-align: center;
        color: rgb(0, 0, 0);
        padding-top: 20px;
        }

        .imagen{

        /*padding: auto;*/
        text-align: center;
        padding-top: 2%;
        padding-left: 3%;
        max-width: 85%;
        }

        .listado{
        padding-left: 20%;
        padding-top: 10px;
        text-align: left;
        padding-bottom: 20px;
    }

    }

    @media only screen and (max-width: 768px){
        .fuenteDescripcion{
            text-align: center;
            color: rgb(92, 88, 88);
            font-size: large;
            font-family: 'Arvo', serif;
            font-style: bold;
            font-weight: 400;
        }

        .listado{
        padding-left: 20%;
        padding-top: 10px;
        text-align: left;
        padding-bottom: 20px;
    }

    }


</style>