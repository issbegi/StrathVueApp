<template>
  <div id="homepage">
    <v-card
    class="mx-auto"
    max-width="1000"
    height="800"
    image="https://ebs.strathmore.edu/img/University-Logo-Vertical-01.png"
    
    theme="light"
  ></v-card>
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item
            src="https://strathmore.edu/wp-content/themes/strathmore/images/slider6.webp"
        
          >
            ></v-carousel-item
          >

          <v-carousel-item
            src="https://sbs.strathmore.edu/wp-content/uploads/2023/05/Strathmore-University-Business-School-A-Must-Watch-Institution-for-Business-Education-in-Africa-web1.png"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="https://sbs.strathmore.edu/wp-content/uploads/2020/10/hs9.jpg"
            cover
          ></v-carousel-item>
        </v-carousel>
      </v-layout>
      <v-layout>
        <v-container>
          <v-row align="center" justify="center">
            <div class="d-flex align-center flex-column">
              <div class="text-subtitle-2"></div>

            


  


              <div class="mt-4 text-subtitle-2"></div>

              <v-card width="1000">
                <template v-slot:title> Accomodation </template>

                <template v-slot:subtitle>  </template>

                <template v-slot:text> Accomodion offered in Strathmore University. </template>
              </v-card>
              


  


              <div class="mt-4 text-subtitle-2"></div>

              <v-card width="1000">
                <template v-slot:title> Location </template>

                <template v-slot:subtitle>  </template>

                <template v-slot:text> Where our Branches are located. </template>
              </v-card>

              <div class="mt-4 text-subtitle-2"></div>

              <v-card width="1000">
                <v-card-item>
                  <v-card-title>Courses</v-card-title>

                  <v-card-subtitle></v-card-subtitle>
                </v-card-item>

                <v-card-text> Courses Offered in Strathmore University. </v-card-text>
              </v-card>
            </div>
          </v-row>
        </v-container>
      </v-layout>
    </v-container>
  </div>
</template>
<script setup>
const variants = ["elevated", "flat", "tonal", "outlined"];


</script>