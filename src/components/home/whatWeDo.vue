<template>
    <v-container class="pa-0">
        <v-layout wrap align-center justify-center row fill-height >
           <v-flex xs12 md3 lg3 class="pa-2">
               <p class="google-font" style="font-size:180%">Qué hacemos?</p>
               <p class="google-font" style="font-size:110%">Los GDGs (Google Developer Groups) son para desarrolladores que estén interesados en la tecnología de desarrollo de Google.</p>

               <p class="google-font" style="font-size:110%">Sobre diferentes tecnologías de Google</p>
               <img src="@/assets/img/svg/angular.svg" width="30vh" alt="" srcset=""> &nbsp;&nbsp;&nbsp;
                <img src="@/assets/img/svg/gcp.svg" width="30vh" alt="" srcset="">&nbsp;&nbsp;&nbsp;
                <img src="@/assets/img/svg/android.svg" width="30vh" alt="" srcset="">&nbsp;&nbsp;&nbsp;
                <img src="@/assets/img/svg/aog.png" width="30vh" alt="" srcset="">&nbsp;&nbsp;&nbsp;
                <img src="@/assets/img/svg/firebase.svg" width="30vh" alt="" srcset="">&nbsp;&nbsp;&nbsp;
                <img src="@/assets/img/svg/tf.svg" width="30vh" alt="" srcset="">
                <br><br>

                <v-btn :href="chapterDetails.GDGProgramWebsite" outline target="_blank" round color="cyan" style="text-transform: capitalize;border-radius:7px;text-transform: capitalize;" flat  class="ml-0 google-font hidden-md-and-down" dark>Learn More</v-btn>

            </v-flex> 
            <v-flex xs12 md9 lg9 class="">
                <v-layout row wrap>

                    <v-flex xs6 sm6 md3 lg3 class="text-xs-center pa-2">
                        <v-icon large style="font-size:300%">chat_bubble</v-icon>
                        <p class="google-font" style="font-size:130%">Charlas</p>
                        <p class="google-font" style="font-size:110%">Actualízate con las últimas noticias y anuncios.</p>
                    </v-flex>

                    <v-flex xs6 sm6 md3 lg3 class="text-xs-center pa-2">
                        <v-icon large style="font-size:300%">code</v-icon>
                        <p class="google-font" style="font-size:130%">Codelabs</p>
                        <p class="google-font" style="font-size:110%">Experiencia práctica y orientación de los miembros de la comunidad.</p>
                    </v-flex>

                    <v-flex xs6 sm6 md3 lg3 class="text-xs-center pa-2">
                        <v-icon large style="font-size:300%">school</v-icon>
                        <p class="google-font" style="font-size:130%">Formaciones</p>
                        <p class="google-font" style="font-size:110%">Compartir conocimientos en diferentes empresas, colegios y universidades.</p>
                    </v-flex>

                    <v-flex xs6 sm6 md3 lg3 class="text-xs-center pa-2">
                        <v-icon large style="font-size:300%">airplay</v-icon>
                        <p class="google-font" style="font-size:130%">Quedadas para eventos en vivo</p>
                        <p class="google-font" style="font-size:110%">Juntarnos para retransmitir un evento importante y poder comentarlo juntos</p>
                    </v-flex>

                </v-layout>
            </v-flex>
        </v-layout>

    </v-container>
</template>

<script>
import ChapterDetails from '@/assets/data/chapterDetails.json'
export default {
    data() {
        return {
            chapterDetails: ChapterDetails
        }
    },
}
</script>
