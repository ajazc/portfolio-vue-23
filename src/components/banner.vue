<template>
    <div class="banner d-flex flex-column justify-center align-items-center  ">
          
          <div class="intro">
            <p class="ma-0 pa-0">Introducción</p>
            <h1 class="heading ma-0 pa-0 "> Ajazc Portfolio </h1>
            <h2 class="secondary-text"> Un portafolio minimalista y <span> moderno</span></h2>
            <v-btn color="accent" outlined class="btn my-8">
                Ver más 
            </v-btn>
          </div>
    </div>
</template>


<script>
export default {
    name:"banner"
}
</script>


<style lang="scss" >
     .banner {
        text-align: left;
        height:100vh;
        width:100vw;
        background-color: var(--main-bg-color);
        padding: 10%;
    }
    
    .intro{
       
        p {
            margin-left: 10px; 
            padding: 0;
            font-size: 1.5em ;
            font-weight: bold;
            color :var(--dark-accent) ;
        };

        span{
            color : var(--dark-accent);
        }

        .btn{
            color: var(--gray);
        }

      
        .secondary-text{
            color: var(--gray) ;
        }

        .heading {
            margin:0px; 
            padding: 0px;
            font-size: 4em ;
            color : var(--highlight-color);
        }

    }


</style>