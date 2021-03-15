<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Alert</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Alert</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-button @click="presentAlert" expand="full"
              >Show Alert</ion-button
            >
          </ion-col>
      </ion-row>
             </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script>
import { 
  IonPage, 
  IonHeader, 
  IonToolbar, 
  IonTitle, 
  IonContent, 
  IonButton, 
  alertController, 
  } from '@ionic/vue';

export default {
  name: 'Tab1',
  components: { 
  IonHeader, 
  IonToolbar, 
  IonTitle, 
  IonContent, 
  IonPage, 
  IonButton, 
  }, 
  methods: {
  async presentAlert() {
      const alert = await alertController.create({
        header: 'Use this lightsaber?',
        message: 'Do you agree to use this lightsaber to do good across the galaxy?',
        buttons: ['DISAGREE','AGREE']
      });
      return alert.present();
  },
    }
};
  </script>