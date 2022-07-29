<template>
  <ion-app>
    <menu-page side="end" content-id="main-content"></menu-page>
    <header-section id="main-content"></header-section>
    <ion-content >
      <ion-router-outlet />
    </ion-content>
  </ion-app>
</template>

<script lang="ts">
import { IonApp, IonRouterOutlet, IonContent } from '@ionic/vue';
import MenuPage from './views/MenuPage.vue';
import HeaderSection from './components/headerSection.vue';

export default{
  name: 'App',
  components: {
    IonApp,
    IonRouterOutlet,
    IonContent,
    MenuPage,
    HeaderSection
}
};
</script>