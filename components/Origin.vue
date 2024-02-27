<template>
    <v-container class="mt-5">
<v-card flat class="">
    <v-tabs
      class=""
      v-model="tab"
      align-tabs="start"
      bg-color="white"
      dark    >
      <v-tab value="one">Tecnologia</v-tab>
      <v-tab value="two">Engenharia</v-tab>
      <v-tab value="three">Infraestrutura</v-tab>
      <v-tab value="four">Arquitetura & Construção</v-tab>
    </v-tabs>

    <v-card-text>
      <v-window v-model="tab">
        <v-window-item value="one">
        <v-row class="mt-10">
          
          <v-col cols="12" md="4" class="align-center align-justify">
            <v-card flat height="600px">
         <v-img class="mt-15" size = '600px' src="https://img.freepik.com/free-photo/cloud-storage-banner-background_53876-108506.jpg?w=996&t=st=1708383423~exp=1708384023~hmac=e24ba3466fba254b19c2b7286c9aa0d29e39132bd637d3d20a31d6e0129fdca5"/>
        </v-card>
      </v-col>
  
      <v-col cols="12" md="4">
        <v-card
        class="mx-auto"
        max-width="344"
        title="BIM"
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
       
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card>
      <v-card
        class="mx-auto"
        max-width="344"
        title="PowerBI"
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
       
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card>
      <v-card
        class="mx-auto"
        max-width="344"
        title=""
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
        
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card>
      <v-card
        class="mx-auto"
        max-width="344"
        title="Avatars"
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
        
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card>
      </v-col>
      <v-col cols="12" md="4">
        <v-card
        class="mx-auto"
        max-width="344"
        title="Avatars"
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
       
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card>
      <v-card
        class="mx-auto"
        max-width="344"
        title="Avatars"
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
       
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card>
      <v-card
        class="mx-auto"
        max-width="344"
        title="Avatars"
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
        
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card>
      <v-card
        class="mx-auto"
        max-width="344"
        title="Avatars"
        flat
        prepend-avatar="https://cdn.vuetifyjs.com/images/logos/v-alt.svg"
        
      >
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</v-card-text>
      </v-card> 
      </v-col>
    </v-row>
        </v-window-item>

        <v-window-item value="two">
            <v-card flat height="600px">
         <v-img  size = '600' src="/telas.jpg"/>
        </v-card>
        </v-window-item>

        <v-window-item value="three">
            <v-card flat height="600px">
         <v-img  size = '600' src="/telas.jpg"/>
        </v-card>
        </v-window-item>

        <v-window-item value="four">
            <v-card height="600px">
         <v-img  size = '600' src="/telas.jpg"/>
        </v-card>
        </v-window-item>
      </v-window>
      
    </v-card-text>
  </v-card>
</v-container>
</template>

<script>
  export default {
    data: () => ({
      tab: null,
    }),
  }
</script>