
     <template>


  <v-card
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
  </v-card>














































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
  <!-- > -->
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