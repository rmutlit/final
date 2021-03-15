<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Input</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Input</ion-title>
        </ion-toolbar>
      </ion-header>

      <ion-grid>
            <ion-item>
         <ion-label> Label Positions </ion-label> </ion-item>
         <ion-item>
          <ion-label>Default Label</ion-label>
          <ion-input placeholder="placeholder"></ion-input>
        </ion-item>
        <ion-item>
          <ion-label position="fixed">Fixed Label</ion-label>
          <ion-input placeholder="placeholder"></ion-input>
        </ion-item>
            </ion-grid>

       </ion-content>
  </ion-page>
</template>

<style>
    :root {
      --ion-safe-area-top: 20px;
      --ion-safe-area-bottom: 22px;
    }
</style>

<script>
import { 
  IonPage, 
  IonHeader,
   IonToolbar, 
   IonTitle, 
   IonContent,
   } from '@ionic/vue';

export default  {
  name: 'Tab5',
  components: { 
    IonHeader, 
    IonToolbar,
     IonTitle,
      IonContent, 
      IonPage,
       }
}
</script>