<template>
    <div id="about"> 
      <v-row>
          <v-col class="col-xs-12">
            <!-- add your personal bio paragraphs here in this column -->
            
            <h2> Acerca de Mi</h2>
            <p> Mi nombre es augusto, soy desarrollador de software orientado a web</p>
            <p> Actualmente me encuentro desenpeñandome en un ente gubernamental de la Provincia de Santa Cruz Argentina</p>
            <p> Tambien me dedico a desarrollar sistemas en Slim PHP, PHP Nativo, DJANGO Python, API REST, API SOAP.</p>
          </v-col>
          <v-col class="col-xs-12">
              <v-img src="#" max-width="500px" contain >

              </v-img>
          </v-col>
      </v-row>
    </div>
</template>

<script>
export default {
    name : 'about'
}
</script>


<style lang="scss" scoped > 
    #about{
        padding-left: 10%;

       h2{  
           text-transform: uppercase;
           font-weight: bold;
           color:var(--accent-color);
           padding-top:15px;
        }
        p {
             padding-block: 10px;
             padding-right: 10px;
             font-weight: 400;
             color: var(--gray);
             font-size: 1.3em;
        }
    }

</style>