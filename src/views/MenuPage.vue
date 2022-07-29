<template>
      <ion-menu>
        <ion-header>
          <ion-toolbar translucent>
            <ion-item>
              <ion-title>Menu</ion-title>
              <ion-menu-toggle>
                <h1>X</h1>
              </ion-menu-toggle>
            </ion-item>
          </ion-toolbar>
        </ion-header>
        <ion-content>
          <ion-list>
          <ion-accordion-group>
            <ion-accordion value="first">
              <ion-item slot="header" color="light">
                <ion-label>Who it's for</ion-label>
              </ion-item>
              <div class="ion-padding" slot="content">
                Individaul
              </div>
              <div class="ion-padding" slot="content">
                HR & Employers
              </div>
              <div class="ion-padding" slot="content">
                Health Plans & Value-Based Care 
              </div>
              <div class="ion-padding" slot="content">
                Senior and Medicare
              </div>
              <div class="ion-padding" slot="content">
                School
              </div>
              <div class="ion-padding" slot="content">
                First Content
              </div>
             
            </ion-accordion>
            
           <ion-accordion value="Contect Us">
              <ion-item slot="header" color="light">
                <ion-label>Contect Us</ion-label>
              </ion-item>
              <div class="ion-padding" slot="content">
                Request a Demo
              </div>
              <div class="ion-padding" slot="content">
               Member Community
              </div>
              <div class="ion-padding" slot="content">
                Partnerships
              </div>
              <div class="ion-padding" slot="content">
                Refer Your Company
              </div>
              <div class="ion-padding" slot="content">
                Press
              </div>
              <div class="ion-padding" slot="content">
                General Inquery
              </div>
            </ion-accordion>
            <ion-item>
              <ion-label>About Swortkit</ion-label>
            </ion-item>
           <ion-accordion value="Resource">
              <ion-item slot="header" color="light">
                <ion-label>Resource</ion-label>
              </ion-item>
              <div class="ion-padding" slot="content">
                Getting Start- USer Guide
              </div>
              <div class="ion-padding" slot="content">
                Blog
              </div>
              <div class="ion-padding" slot="content">
                AskA trainer 
              </div>
              <div class="ion-padding" slot="content">
                Before and After Transformation
              </div>
              <div class="ion-padding" slot="content">
                Exercise Library
              </div>
              <div class="ion-padding" slot="content">
                Shop Sworkit Gear
              </div>
            </ion-accordion>
            <ion-item>
              <RouterLink to="/login">login</RouterLink>
            </ion-item>
          </ion-accordion-group>
          </ion-list>
          <ion-button class="ion-button" shape="round">try for free</ion-button>
        </ion-content>
      </ion-menu>
</template>

<script lang="ts">
import { RouterLink } from 'vue-router';
import { 
  IonAccordionGroup,
  IonAccordion,
  IonLabel,
  IonContent, 
  IonHeader, 
  IonItem, 
  IonList, 
  IonMenu, 
  IonTitle, 
  IonToolbar,
  
  // menuController,
  // IonButton
} from '@ionic/vue';
export default {
  name:"MenuPage",
  components:{ 
  IonAccordionGroup,
  IonAccordion,
  IonLabel,
  IonContent, 
  IonHeader, 
  IonItem, 
  IonList, 
  IonMenu, 
  IonTitle, 
  IonToolbar,
  // menuController,
  // IonButton
},



}
</script>

<style>

</style>