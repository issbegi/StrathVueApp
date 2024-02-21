<template>
    <div id="homepage">
      <v-container>
        <v-layout column>
          <v-carousel>
            <v-carousel-item
              src="https://alumni.strathmore.edu/wp-content/uploads/2023/03/ALUMNI-4.jpg&quot"
          
            >
              ></v-carousel-item
            >
  
            <v-carousel-item
              src="https://alumni.strathmore.edu/wp-content/uploads/2023/08/DSC_0737-1-1-scaled.jpg&quot"
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
                  <template v-slot:title>Alumni Services </template>
  
                  <template v-slot:subtitle>Card Registration  </template>
  
                  <template v-slot:text>600 ksh which is renewable annually.Allows access into Strathmore University premises except for the library. </template>
                </v-card>
                
  
  
    
  
  
                <div class="mt-4 text-subtitle-2"></div>
  
                <v-card width="1000">
                  <template v-slot:title>Medical Centre Services </template>
  
                  <template v-slot:subtitle>  </template>
  
                  <template v-slot:text> 10% discount for consultation

( This is to ensure that the alumni stays healthy and can select medical services at the University Medical Centre) </template>
                </v-card>
  
                <div class="mt-4 text-subtitle-2"></div>
  
                <v-card width="1000">
                  <v-card-item>
                    <v-card-title>Merchandise</v-card-title>
  
                    <v-card-subtitle></v-card-subtitle>
                  </v-card-item>
  
                  <v-card-text> Branded Masks, Alumni lapel pins, Thermal Mugs, Umbrellas, Notebooks, Hoodies, Laptop Bags </v-card-text>
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