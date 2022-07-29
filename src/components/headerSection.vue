<template>
  <ion-header :translucent="true">
  <ion-toolbar>    
    <ion-title>
      <router-link to="/home"><b>SWORKIT</b></router-link>
    </ion-title>
 

   <ion-buttons slot="end">
    <ion-button class="ion-button" shape="round" >try for free</ion-button>
      <ion-menu-button></ion-menu-button>
    </ion-buttons>
  </ion-toolbar>
    </ion-header>
</template>

<script lang="ts">
import { RouterLink } from "vue-router"
import {
IonHeader,
IonToolbar,
IonTitle,
IonButton,
IonButtons,
} from "@ionic/vue"
export default {
  name:"HeaderSection",
  components:{
    IonHeader,
    IonToolbar,
    IonTitle,
    IonButton,
    IonButtons,
  }

}
</script>

<style scoped>
.ion-button {
  color: white;
  background-color: rgb(220, 113, 31);
  ;
}
</style>