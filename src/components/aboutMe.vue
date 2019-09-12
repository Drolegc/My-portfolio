<template>

    <div class="aboutMe">
        <div class="row d-flex">
            <div class="col-md-6 col-sm-12">
                <div>
                <h2>About me</h2>
                <p>Hi,i'm Leandro and a full stack developer.</p>
                <p>
                    I'm from Uruguay and i currently studing Computer Sience
                    <br> in the "Centro Universitario Regional
                    Este", in Maldonado
                </p>
                <p>
                    Before start my carreer i studied Art in high school 
                    <br> and i took a course about Social Psicology
                </p>
                <p>
                    Seens child i love create things, from draws and paints, 
                    <br>and now with technology i project myself
                    creating any kind of things.
                </p>
                </div>
                <div class="d-flex">
                    <a class="mr-2" href="https://www.linkedin.com/in/leandro-gonz%C3%A1lez-cuello-672287189/" ><font-awesome-icon class="icon" size="2x" :icon="['fab', 'linkedin']"></font-awesome-icon></a>
                    <a class="mr-2" href="https://github.com/Drolegc"><font-awesome-icon :icon="['fab', 'github']" size="2x" class="icon" ></font-awesome-icon></a>
                    <a class="mr-2" href="https://mail.google.com/mail/?view=cm&fs=1&to=drolegc@gmail.com"><font-awesome-icon class="icon" icon='envelope' size="2x"></font-awesome-icon></a>
                </div>
            </div>
            <div class="col-md-6 col-sm-12 img text-center">
                <img class=""
                    :src="imgDog"
                    alt="imgDog">
            </div>
        </div>
    </div>

</template>

<script>

    export default {
        name: 'aboutMe',
        props:['imgDog']
    }

</script>

<style>

    .aboutMe .icon{
        color: #2c3e50;
    }

</style>