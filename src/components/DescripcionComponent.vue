<template>
    <div class="titulo is-spaced">
        Hola! Soy Axl Galicia
    </div>
    <div class="subtitulo">
        Estudiante de ingenieria electronica
    </div>
    <div class="subtitulo2 columns">
        <div class="estudios column">
            Estudios en
        </div>
        <div class="estudiosLogo column">
            <img src="../assets/logo_usac.svg" width="200" height="200">
        </div>
        
    </div>
</template>

<script setup>
//Imagen de <a href="https://pixabay.com/es/users/geralt-9301/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=3537401">Gerd Altmann</a> en <a href="https://pixabay.com/es//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=3537401">Pixabay</a>

</script>

<style scoped>
/*.titulo
{
    font-size: 45px;
    font-family: 'Arvo', serif;
    font-style: bold;
    font-weight: 700;
}*/

.subtitulo
{
    font-size: x-large;
    font-family: 'Arvo', serif;
    font-style: normal;
    font-weight: 400;
}
.subtitulo2{
    /*text-align: left;
    margin-top: 5%;
    margin-left: 10%;
    font-size: medium;
    font-family: 'Arvo', serif;
    font-style: normal;*/
}

@media only screen and (max-width: 768px) {
    .titulo
{
    font-size: 35px;
    font-family: 'Arvo', serif;
    font-style: bold;
    font-weight: 700;
}

    .estudios{
    display: flex;
    justify-content: center;
    /*background-color: rgb(255, 94, 0);*/

    padding-top: 10%;
    padding-bottom: 0%;
    font-size: x-large;
    font-family: 'Arvo', serif;
    font-style: normal;
    font-weight: 400;
    }   

.estudiosLogo{
    display: flex;
    justify-content: center;
    /*background-color: rgb(42, 165, 120);*/

    padding-top: 2%;
}
}

@media only screen and (min-width: 769px) {

    .titulo
{
    font-size: 45px;
    font-family: 'Arvo', serif;
    font-style: bold;
    font-weight: 700;
}

    .estudios{
    display: flex;
    justify-content: right;
    /*background-color: blue;*/
    font-size: x-large;
    font-family: 'Arvo', serif;
    font-style: normal;
    font-weight: 400;
    padding-top: 8%;
}

.estudiosLogo{
    display: flex;
    /*background-color: brown;*/

    padding-top: 5%;
}

}

</style>