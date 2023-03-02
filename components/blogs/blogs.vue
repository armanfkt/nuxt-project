
     <template>
<template>
  <v-card
    max-width="400"
    class="mx-auto"
  >
    <!-- <v-system-bar
      color="pink darken-2"
      dark
    >
      <v-spacer></v-spacer>

      <v-icon>mdi-window-minimize</v-icon>

      <v-icon>mdi-window-maximize</v-icon>

      <v-icon>mdi-close</v-icon>
    </v-system-bar>

    <v-app-bar
      dark
      color="pink"
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>My Music</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
    </v-app-bar> -->

    <v-container>
      <v-row dense>
        <v-col cols="12">
          <v-card
            color="#385F73"
            theme="dark"
          >
            <v-card-title class="text-h5">
              Unlimited music now
            </v-card-title>

            <v-card-subtitle>Listen to your favorite artists and albums whenever and wherever, online and offline.</v-card-subtitle>

            <v-card-actions>
              <v-btn variant="text">
                Listen Now
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>

        <v-col cols="12">
          <v-card
            color="#1F7087"
            theme="dark"
          >
            <div class="d-flex flex-no-wrap justify-space-between">
              <div>
                <v-card-title class="text-h5">
                  Supermodel
                </v-card-title>

                <v-card-subtitle>Foster the People</v-card-subtitle>

                <v-card-actions>
                  <v-btn
                    class="ms-2"
                    variant="outlined"
                    size="small"
                  >
                    START RADIO
                  </v-btn>
                </v-card-actions>
              </div>

              <v-avatar
                class="ma-3"
                size="125"
                rounded="0"
              >
                <v-img src="https://cdn.vuetifyjs.com/images/cards/foster.jpg"></v-img>
              </v-avatar>
            </div>
          </v-card>
        </v-col>

        <v-col cols="12">
          <v-card
            color="#952175"
            theme="dark"
          >
            <div class="d-flex flex-no-wrap justify-space-between">
              <div>
                <v-card-title class="text-h5">
                  Halcyon Days
                </v-card-title>

                <v-card-subtitle>Ellie Goulding</v-card-subtitle>

                <v-card-actions>
                  <v-btn
                    class="ms-2"
                    icon="mdi-play"
                    variant="text"
                  ></v-btn>
                </v-card-actions>
              </div>

              <v-avatar
                class="ma-3"
                size="125"
                rounded="0"
              >
                <v-img src="https://cdn.vuetifyjs.com/images/cards/halcyon.png"></v-img>
              </v-avatar>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-card>
</template>

  <!-- <v-card
    class="overflow-auto mx-auto"
    max-height="300"
    width="448"
  >
    <v-toolbar color="primary">
      <v-toolbar-title>My Document</v-toolbar-title>

      <v-spacer></v-spacer>

      <template v-slot:append>
        <v-switch
          v-model="sticky"
          label="Sticky Banner"
          hide-details
          color="secondary"
        ></v-switch>
      </template>
    </v-toolbar>

    <v-banner
      :sticky="sticky"
      lines="one"
    >
      <template v-slot:text>
        We can't save your edits while you are in offline mode.
      </template>

      <template v-slot:actions>
        <v-btn color="deep-purple-accent-4">
          Go Online
        </v-btn>
      </template>
    </v-banner>

    <v-card-text class="bg-grey-lighten-4">
      <v-sheet
        class="mx-auto"
        height="300"
      ></v-sheet>
    </v-card-text>

    <v-footer
      class="justify-center"
      color="primary"
    >
      End of Content
    </v-footer>
  </v-card> -->


  
  
  <!-- <div>
    <v-breadcrumbs :items="items">
      <template v-slot:divider>
        <v-icon icon="mdi-forward"></v-icon>
      </template>
    </v-breadcrumbs>

    <v-breadcrumbs :items="items">
      <template v-slot:divider>
        <v-icon icon="mdi-chevron-right"></v-icon>
      </template>
    </v-breadcrumbs>
  </div> -->
  








































    <!-- <v-banner
    style="background-color: darkorange;"
  icon="mdi-vuetify"
  lines="three"
  text="..."
  stacked
  
>
  <template v-slot:actions>
    <v-btn style="background-color:darkturquoise ;">Click me</v-btn>
  </template>
</v-banner> -->






  <!-- <v-toolbar title="Application" color="grey-lighten-3">
    <v-btn stacked>
      <v-badge
        color="success"
        dot
      >
        <v-icon icon="mdi-newspaper-variant-outline"></v-icon>
      </v-badge>

      News
    </v-btn>

    <v-btn stacked>
      <v-badge
        dot
        color="primary"
      >
        <v-icon icon="mdi-post"></v-icon>
      </v-badge>

      Blog
    </v-btn>

    <v-btn
      stacked
      variant="tonal"
      
      color="secondary"
    >
      <v-icon icon="mdi-login"></v-icon>

      Login
    </v-btn>
  </v-toolbar> -->






    <!-- <div class="d-flex align-center justify-space-around">
    <v-avatar color="primary" size="large">
      120
    </v-avatar>

    <v-avatar color="secondary">
      48
    </v-avatar>

    <v-avatar color="info" size="x-large">
      64
    </v-avatar>
  </div> -->
  
  





  <!-- <v-sheet
    border="md"
    class="pa-6 text-white mx-auto"
    color="blue"
    max-width="400"
  >
    <h4 class="text-h5 font-weight-bold mb-4">Your Privacy</h4>

    <p class="mb-8">
      This business determines the use of personal data collectied on our media properties and across the internet. We may collect data that you submit to us directly or data that we collect automatically including from cookies (such as device information or IP address).

      <br>
      <br>

      Please read our <a href="#" class="text-red-accent-2">Privacy Policy</a> to learn about our privacy practices or click "Your Preferences" to exercise control over your data.
    </p>

    <v-btn
      block
      class="text-none text-black mb-4"
      color="red-accent-2"
      size="x-large"
      variant="flat"
    >
      Accept
    </v-btn>

    <v-btn
      block
      class="text-none text-black"
      color="red"
      size="x-large"
      variant="outlined"
    >
      Your Preferences
    </v-btn>
  </v-sheet> -->








  <!-- <v-sheet -->
    <!-- elevation="12" -->
    <!-- max-width="600" -->
    <!-- rounded="lg" -->
    <!-- width="100%" -->
    <!-- class="pa-4 text-center mx-auto" -->
    
    <!-- <v-icon -->
      <!-- class="mb-5" -->
      <!-- color="success" -->
      <!-- icon="mdi-check-circle" -->
      <!-- size="112" -->
    <!-- ></v-icon> -->
<!--  -->
    <!-- <h1 class="text-h5 mb-6">You reconciled this account</h1> -->
<!--  -->
    <!-- <p class="mb-4 text-medium-emphasis text-body-2"> -->
      <!-- To see a report on this reconciliation, click <a href="#" class="text-decoration-none text-info">View reconciliation report.</a> -->
<!--  -->
      <!-- <br> -->
<!--  -->
      <!-- Otherwise, you're done! -->
    <!-- </p> -->
<!--  -->
    <!-- <v-divider class="mb-4"></v-divider> -->
<!--  -->
    <!-- <div class="text-end"> -->
      <!-- <v-btn -->
        <!-- class="text-none" -->
        <!-- color="success" -->
        <!-- rounded -->
        <!-- variant="flat" -->
        <!-- width="90" -->
      <!-- > -->
        <!-- Done -->
      <!-- </v-btn> -->
    <!-- </div> -->
  <!-- </v-sheet> -->
</template>



<script>

export default{
    name:"Blogs"
    
}


</script>