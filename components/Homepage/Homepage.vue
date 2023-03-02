<template>
    <v-container class="homepage">
        <v-row>
            <v-col cols="12" sm="8" md="3">
                <nuxt-link to="/product-overview">Products</nuxt-link>
            </v-col>
            
            <v-col cols="12" sm="4" md="3">
                <nuxt-link to="contact_gus.vue">contact-us</nuxt-link>
            </v-col>
            
            <v-col cols="12" sm="6" md="3">
                <div class="homepage-box">
                    Hello World!
                </div>
            </v-col>
            
            <v-col cols="12" sm="6" md="3">
                <div class="homepage-box">
                    <span class="homepage-box-text">
                        Hello World!
                    </span>
                </div>
            </v-col>

            <v-col>
                <nuxt-link to="/blogs">blogs</nuxt-link>
            </v-col>

            <v-col>
                <nuxt-link to="profiles">profiles</nuxt-link>
            </v-col>
            <v-col>
                <nuxt-link to="about_us">about_us</nuxt-link>
            </v-col>
        </v-row>
        
        
        <v-row justify="space-between" class="homepage-box-text-icon">
              <v-col>
              <v-btn 
              icon="mdi-heart"
              color="primary"
              ></v-btn>
              <v-icon>mdi-heart</v-icon>
            </v-col>
      
            <v-col>
              <v-btn
              icon="mdi-star"
              color="secondary"
                ></v-btn>
                <v-icon>mdi-heart</v-icon>
            </v-col>
      
            <v-col>
              <v-btn
                icon="mdi-cached"
                color="info"
              ></v-btn>
              <v-icon>mdi-heart</v-icon>
            </v-col>
      
            <v-col>
              <v-btn
                icon="mdi-thumb-up"
                color="success"
              ></v-btn>
              <v-icon>mdi-heart</v-icon>
            </v-col>
          </v-row>
      
          <v-row justify="space-between" class="homepage-box-text-icon-2">
            <v-col>
              <v-btn
                icon
                color="primary"
              >
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </v-col>
      
            <v-col>
              <v-btn
                icon
                color="secondary"
              >
                <v-icon>mdi-star</v-icon>
              </v-btn>
            </v-col>
      
            <v-col>
              <v-btn
                icon
                color="info"
              >
                <v-icon>mdi-cached</v-icon>
              </v-btn>
            </v-col>
      
            <v-col>
              <v-btn
                icon
                color="success"
              >
                <v-icon>mdi-thumb-up</v-icon>
              </v-btn>
            </v-col>
          </v-row>
    </v-container>
    


</template>

<script>
export default{
    name:'Homepage',
}
</script>
