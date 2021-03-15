<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Button</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Button</ion-title>
        </ion-toolbar>
      </ion-header>

     <ion-grid>
        <ion-row>
          <ion-col>
            <ion-text>SMALL SIZE</ion-text>  </ion-col>  </ion-row>
            <ion-row>
            <ion-col>
            <ion-button size="small">DEFAULT</ion-button> 
            <ion-button size="small" color="secondary">SECONDARY</ion-button> </ion-col> </ion-row>
           <ion-row>
            <ion-col>
            <ion-button size="small" color="tertiary">TERTIARY</ion-button> </ion-col> </ion-row>
          <ion-row>
            <ion-col>
              <header>DEFAULT SIZE</header>
        <ion-button color="success">SUCCESS</ion-button>
        <ion-button color="warning">WARNING</ion-button> <br>
        <ion-button color="danger">DANGER</ion-button>
     </ion-col> </ion-row>
     <ion-row>
            <ion-col>
          <header>LARGE SIZE</header>
        <ion-button size="large" color="light">LIGHT</ion-button>
        <ion-button size="large" color="medium">MEDIUM</ion-button>
        <ion-button size="large" color="dark">DARK</ion-button>
              </ion-col> </ion-row>
          <ion-row><ion-col>
          <header>BLOCK WIDTH</header>
        <ion-button expand="block">A BLOCK BUTTON</ion-button>
          </ion-col> </ion-row>
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
   IonButton
   } from '@ionic/vue';

export default  {
  name: 'Tab3',
  components: { 
    IonHeader, 
    IonToolbar,
     IonTitle,
      IonContent, 
      IonPage,
      IonButton
       }
}
</script>