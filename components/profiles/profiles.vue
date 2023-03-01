<template>
    <v-contaner>
        <v-row>
            <v-col cols="12" sm="6" md="3">
                profiles
            </v-col>

            <v-col cols="12" sm="6" md="2">
                <nuxt-link to="/">back to home</nuxt-link>
                
            </v-col>
            <v-col cols="12" sm="12" md="12">
                <v-toolbar :elevation="8" title="Application" style="background-color:red ;">  
                    <v-btn style="margin-left:150px ; color: blue; background-color: aquamarine;">
                     menu
                    </v-btn>
                    <v-btn style="margin-left:150px ;color: blue;background-color: aquamarine;">
                    files
                    </v-btn>
                    <v-btn style="margin-left:150px ;color: blue;background-color: aquamarine;">
                     edits
                    </v-btn>
                    <v-btn  style="margin-left:150px ;color: blue;background-color: aquamarine;">
                     numbers
                    </v-btn>
                </v-toolbar>
            </v-col>
            <v-sheet style="background-color: aqua;" :height="250" :width="1200"> <v-allert text="hello world!"></v-allert></v-sheet>     
            <v-col>
            </v-col>
        </v-row>
    </v-contaner>
</template>

<script>
export default{
    name:"Profiles"
}

</script>
