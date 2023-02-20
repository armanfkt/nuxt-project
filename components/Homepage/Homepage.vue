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
                    Hello World!
                </div>
            </v-col>

            <v-col>
                <nuxt-link to="/blogs">blogs</nuxt-link>
            </v-col>

            <v-col>
                <nuxt-link to="profiles">profiles</nuxt-link>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default{
    name:'Homepage',
}
</script>
