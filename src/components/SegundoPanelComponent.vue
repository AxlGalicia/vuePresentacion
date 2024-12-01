<template>
    <div class="skills" id="habilidades">
        <div class="titulo">
            Habilidades
        </div>
        <div class="columns contenedorColumnas">
            <div class="column caja1">
                <div class="content is-normal">
                    <div class="tituloCaja title is-4">
                        Lenguajes de Programación
                    </div>

                    <ul class="subtitle is-5">
                        <li>Java (Intermedio)</li>
                        <progress class="progress is-primary" value="55" max="100">50%</progress>
                        <li>C# (Intermedio)</li>
                        <progress class="progress is-primary" value="55" max="100">55%</progress>
                        <li>Visual Basic (Intermedio)</li>
                        <progress class="progress is-primary" value="50" max="100">55%</progress>
                        <li>Javascript (Básico-Intermedio)</li>
                        <progress class="progress is-primary" value="35" max="100">30%</progress>
                        <li>Html (Básico-Intermedio)</li>
                        <progress class="progress is-primary" value="35" max="100">30%</progress>
                        <li>Css (Básico)</li>
                        <progress class="progress is-primary" value="30" max="100">25%</progress>
                    </ul>
                </div>
            </div>
            <div class="column caja2">
                <div class="content is-normal">
                    <div class="tituloCaja title is-4">
                        Tecnologías
                    </div>
                   
                    <ul class="subtitle is-5">
                        <li>.NET</li>
                        <progress class="progress is-primary" value="55" max="100">50%</progress>
                        <li>Base de datos</li>
                        <progress class="progress is-primary" value="50" max="100">35%</progress>
                        <li>Docker</li>
                        <progress class="progress is-primary" value="25" max="100">25%</progress>
                        <li>Arduino</li>
                        <progress class="progress is-primary" value="25" max="100">25%</progress>
                        <li>Vue3</li>
                        <progress class="progress is-primary" value="35" max="100">25%</progress>
                        <li>Git</li>
                        <progress class="progress is-primary" value="50" max="100">30%</progress>
                    </ul>
                </div>
            </div>
            <div class="column caja3">
                <div class="content is-normal">
                    <div class="tituloCaja title is-4">
                        Competencias Clave
                    </div>
                    
                    <ul class="subtitle is-5">
                        <li class="separador">Inglés B1 Técnico</li>
                        <li class="separador">Ofimática</li>
                        <li class="separador">Razonamiento lógico</li>
                        <li class="separador">Trabajo en equipo</li>
                        <li class="separador">Adaptabilidad a tecnologías nuevas</li>
                        <li class="separador">Capacidad de resolución de problemas</li>
                        <li class="separador">Entendimiento intermedio de procesadores de pago</li>
                    </ul>
                </div>
            </div>
            <div class="column caja4">
                <div class="content is-normal">
                    <div class="tituloCaja title is-4">
                        Otras habilidades
                    </div>

                    <ul class="subtitle is-5">
                        <li class="separador">Conocimiento del sistema Linux</li>
                        <li class="separador">Conocimiento de Redes básico</li>
                        <li class="separador">Conocimiento Circuitos Electrónicos</li>
                        <li class="separador">Conocimiento en Microprocesadores</li>
                        <li class="separador">Conocimiento de consumo de Web APIs</li>
                        <li class="separador">Conocimiento de Sql Server</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
    .skills{
        background-color: rgb(0, 0, 0);
        padding-bottom: 10px;
        border-radius: 30px;
    }

    .titulo{
        font-size: xx-large;
        font-family: 'Arvo', serif;
        font-style: bold;
        font-weight: 700;
        text-align: center;
        color: rgb(255, 255, 255);
        padding: 20px;
    }

    .caja1{
        /*background-color: aliceblue;*/
        background-color: #272627cc;
        margin: 10px;
        /*height: 200px;*/
        padding: 20px;
        border-radius: 20px;
        /*border: 5px solid transparent;*/
        border-width: 2px solid;
        border: 4px solid;
        --tw-border-opacity: 1;
        border-color: rgb(214 0 170/var(--tw-border-opacity));

        /*--tw-ring-color: rgba(59,130,246,.5);
        --tw-shadow: 0 2px 10px 4px rgba(65,65,65,.2);
        --tw-shadow-colored: 0 2px 10px 4px var(--tw-shadow-color);
        --tw-ring-offset-shadow: 0 0 #0000;
        --tw-ring-shadow: 0 0 #0000;
        box-shadow: var(--tw-ring-offset-shadow,0 0 #0000),var(--tw-ring-shadow,0 0 #0000),var(--tw-shadow);*/

        /*box-shadow: 0px 0px 3px 3px #4d4c4ecc;*/
    }

    .caja2{
        /*background-color: aliceblue;*/
        background-color: #272627cc;
        margin: 10px;
        /*height: 200px;*/
        padding: 20px;
        border-radius: 20px;
        /*border: 5px solid transparent;*/
        border-width: 2px solid;
        border: 4px solid;
        /*--tw-border-opacity: 1;
        border-color: rgb(214 0 170/var(--tw-border-opacity));*/

        --tw-border-opacity: 1;
        border-color: rgb(245 125 20/var(--tw-border-opacity));
        box-shadow: 0px 0px 3px 3px #4e4d4ccc;
    }

    .caja3{
        /*background-color: aliceblue;*/
        background-color: #272627cc;
        margin: 10px;
        /*height: 200px;*/
        padding: 20px;
        border-radius: 20px;
        /*border: 5px solid transparent;*/
        border-width: 2px solid;
        border: 4px solid;
        --tw-border-opacity: 1;
        border-color: rgb(214 0 170/var(--tw-border-opacity));
        box-shadow: 0px 0px 3px 3px #4d4c4ecc;
    }

    .caja4{
        /*background-color: aliceblue;*/
        background-color: #272627cc;
        margin: 10px;
        /*height: 200px;*/
        padding: 20px;
        border-radius: 20px;
        /*border: 5px solid transparent;*/
        border-width: 2px solid;
        border: 4px solid;
        /*--tw-border-opacity: 1;
        border-color: rgb(214 0 170/var(--tw-border-opacity));*/

        --tw-border-opacity: 1;
        border-color: rgb(245 125 20/var(--tw-border-opacity));
        box-shadow: 0px 0px 3px 3px #4e4d4ccc;
    }

    .caja1:hover{
        box-shadow: 0px 0px 10px 3px #cddfed8d;
    }
    .caja2:hover{
        box-shadow: 0px 0px 10px 3px #cddfed8d;
    }
    .caja3:hover{
        box-shadow: 0px 0px 10px 3px #cddfed8d;
    }
    .caja4:hover{
        box-shadow: 0px 0px 10px 3px #cddfed8d;
    }

    .tituloCaja{
        text-align: center;
        color: blueviolet;
        margin-bottom: 50px;
    }
    li{
        color: white;

    }

    .separador{
        margin-top: 20px;
    }
    .contenedorColumnas{
        padding: 20px;
        padding-bottom: 40px;
    }

</style>