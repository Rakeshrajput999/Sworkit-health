<template>
      <IonToolbar>
        <h1>Let us help you achieve your fitness goals</h1>
        <p>Get answers to your toughest fitness and nutrition challenges plus helpful tips to help you get in shape and stay in shape for life!</p>
        <ion-item>
          <ion-input placeholder="Email Address"></ion-input>
          <ion-button>Submit</ion-button>
        </ion-item>
        <ion-grid>
          <ion-row>
            <ion-col>For Individual</ion-col>
            <ion-col>Buy Sworkit as a gift </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>For Employers</ion-col>
            <ion-col>Shop Swarkit Gear </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>Refer Your Company</ion-col>
            <ion-col>Sworkit User Guide </ion-col>
          </ion-row>
            <ion-col>
          <div>For Health Plans</div>
          <div>Partnerships</div>
          <div>Sworkit Player</div>
          </ion-col>
          <ion-row>
            <ion-col>Help Center</ion-col>
            <ion-col>follow Us </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <div >contect us</div>
              <div>About  us</div>
              <div>Press</div>
            </ion-col>
            <ion-col> </ion-col>
          </ion-row>
          
            <ion-grid >
              <ion-row>
                <ion-col size="6">terms and Service</ion-col>
                <ion-col size="6">Privecy Policy</ion-col>
              </ion-row>
            </ion-grid>
            @2022 Swortkit  by Nexarcise Inc.
          
        </ion-grid>
      </IonToolbar>
  
</template>

<script lang="ts">
import {
  IonGrid,
  IonRow,
  IonCol,
  IonInput,
  IonToolbar,
  IonButton
} from '@ionic/vue'


export default {
  name:"FooterPage",
  components: {
    IonGrid,
    IonRow,
    IonCol,
    IonInput,
    IonToolbar,
    IonButton
  }

}
</script>

<style>

</style>