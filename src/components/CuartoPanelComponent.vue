<template>
    <div class="panelApi">
        <div class="card contenedor">
            <div class="card-content">
                <p class="title funcionesTecnologias">
        En los siguientes enlaces puede encontrar una Web Api .NET demostrativa con las siguientes funcionalidades que puede probar.
                </p>
                <div class="descripcionTecnologias">
                    <p>
                        <ol class="listado">
                        <li>
                    Paginación
                        </li>
                        <li>
                    Autenticación con JWT
                        </li>
                        <li>
                    Guardado de passwords con HMACSHA512
                        </li>
                        <li>
                    Uso de EntityFrameworkCore
                        </li>
                        <li>
                    CRUD Básico
                        </li>
                        <li>
                    Uso de Spaces Digital Ocean
                        </li>
                        <li>
                    Despliegue con Docker
                        </li>
                        <li>
                    Uso de Bump.sh para documentación
                        </li>
                        </ol>
                    </p>
                </div>
        <div class="aclaracion">
            Puede utilizar Postman o algun otro cliente para probar APIs.
        </div>
    </div>
    <footer class="card-footer">
        <p class="card-footer-item">
        <span class="centrado-texto">
            Web Api <a href="https://bump.sh/axlga/doc/volcanes">documentación</a>
        </span>
        </p>
        <p class="card-footer-item">
        <span class="centrado-texto">
            Web Api <a href="https://volcan-gt.lat">página</a>
        </span>
        </p>
    </footer>
    </div>
    </div>
</template>

<script setup>
</script>

<style scoped>

    .panelApi{
        /*height: 50px;*/
        /*background-color: aliceblue;*/
        padding: 40px;
        
    }
    .contenedor{
        /*background: linear-gradient(to right,rgb(207, 208, 208), rgb(152, 245, 228));*/
        /*background: rgb(242,241,247);
        background: linear-gradient(90deg, rgba(242,241,247,1) 0%, rgba(180,223,220,1) 46%, rgba(137,217,233,1) 100%);*/
        background: rgb(250,163,91);
        background: linear-gradient(90deg, rgba(250,163,91,1) 0%, rgba(180,223,220,1) 60%, rgba(137,217,233,1) 100%);
        border-radius: 20px;
        box-shadow: 0px 0px 25px black;
    }

    .funcionesTecnologias{
        color: rgb(0, 0, 0);
        text-align: center;
    }

    .listado{
        text-align: left;
        color: rgb(92, 88, 88);
        font-size: large;
        font-family: 'Arvo', serif;
        font-style: bold;
        font-weight: 400;
    }

    .descripcionTecnologias{
        display: flex;
        justify-content: center;
    }

    .aclaracion{
        margin-top: 15px;
        display: flex;
        justify-content: end;
    }

    @media only screen and (max-width: 768px){

        .panelApi{
        /*height: 50px;*/
        /*background-color: aliceblue;*/
        padding: 30px;
        }
        .funcionesTecnologias{
            text-align: center;
            color: rgb(0, 0, 0);
            font-size: larger;
            font-family: 'Arvo', serif;
            font-style: bold;
            font-weight: 400;
        }

        .listado{
        text-align: left;
        color: rgb(92, 88, 88);
        font-size: medium;
        font-family: 'Arvo', serif;
        font-style: bold;
        font-weight: 400;
        }
        .descripcionTecnologias{
        display: flex;
        justify-content: center;
        padding-left: 15px;
        padding-right: 0px;
        }

        .centrado-texto{
            text-align: center;
        }

    }

    @media only screen and (min-width: 769px){



    }

    @media only screen and (min-width: 1320px){

        .panelApi{
        /*height: 50px;*/
        /*background-color: aliceblue;*/
        padding-top: 30px;
        
    }
    .contenedor{
        /*background: linear-gradient(to right,rgb(207, 208, 208), rgb(152, 245, 228));*/
        /*background: rgb(242,241,247);
        background: linear-gradient(90deg, rgba(242,241,247,1) 0%, rgba(180,223,220,1) 46%, rgba(137,217,233,1) 100%);*/
        background: rgb(250,163,91);
        background: linear-gradient(90deg, rgba(250,163,91,1) 0%, rgba(180,223,220,1) 60%, rgba(137,217,233,1) 100%);
        border-radius: 20px;
        box-shadow: 0px 0px 25px black;
        margin-left: 10%;
        margin-right: 10%;
    }

    }

</style>