<template>
  <v-content class="pa-0">

    <v-container fluid class="mt-3 mb-0">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md10 class="my-0">
            <p class="google-font mb-0" style="font-size:200%;color:#616161">Nuestra alineación de grandes pensadores.</p>
            <p class="google-font mt-0 mb-0" style="font-size:110%">Google es conocido en todo el mundo. Todos buscan con Google, navegan con Maps y escribiéndose con Gmail... Para usuarios sencillos, son servicios que simplemente funcionan, pero no para nosotros. Los desarrolladores ven mucho más: API, problemas de escalabilidad, pilas de tecnología complejas. Y de eso se trata el GDG.</p>

            <p class="google-font mt-3 mb-0" style="font-size:110%">Nuestro objetivo es organizar el espacio y el canal para conectar a los mejores expertos de la industria con la audiencia de Santander para impulsar el desarrollo de la Tecnología. Y nuestro equipo es: </p>

        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <coreTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">

        </v-flex>
      </v-layout>
    </v-container>

   


  </v-content>
  
</template>

<script>
import TeamDetails from '@/assets/data/chapterDetails.json'
import coreTeam from '@/components/team/coreTeam'
  export default {
    components: {
      coreTeam
    },
    data() {
      return {
        TeamDetails: TeamDetails,
      }
    },
  }
</script>
