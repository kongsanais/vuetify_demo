<template>
  <div id="home">
   <v-container fluid>

     <div v-if="false">
     <h1>Home</h1>
     <p class="black lighten-3 white--text">test texts</p>
     <p class="text-uppercase">test show text</p>
     <v-btn class="primary black--text mr-5 ">run</v-btn>
     <v-btn fab class="primary black--text mr-5"><i class="material-icons">&#xE87C;</i></v-btn>
     <v-btn class="primary black--text mr-5">
       <i class="material-icons">&#xE87C;</i>
       ok
      </v-btn>
      <v-container>
         <v-btn class="success hidden-md-and-up ma-2" >Only show in sm and xs</v-btn>
         <br>
         <v-btn class="success hidden-md-only ma-2" >Hidden only md </v-btn>
      </v-container>
     </div>

     
     <v-row no-gutters>

       <v-col cols="6" md="4">
         <v-btn outlined block color="success">1</v-btn>
       </v-col>

       <v-col cols="6" md="4" >
         <v-btn outlined block color="success">2</v-btn>
       </v-col>

       <v-col cols="12" sm="12" md="4" >
         <v-btn outlined block color="success">3</v-btn>
       </v-col>

     </v-row>

     <!-- flex demo -->
     <v-row no-gutters class="justify-center align-content-center" style="height:200px;background-color:blue;">

       <v-col cols="2">
         <v-btn block color="success">text</v-btn>
       </v-col>

        <v-col cols="2">
        <v-btn block color="success">text </v-btn>
       </v-col>

     </v-row>


   </v-container>
  </div>
</template>
<script>
export default {
  name:"home"
}
</script>

<style>

</style>