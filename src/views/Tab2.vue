<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Card</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Card</ion-title>
        </ion-toolbar>
      </ion-header>
      
       <ion-card>
           <ion-card-header>
     <img src="https://media.xconomy.com/wordpress/wp-content/images/2014/03/06185145/Madison-skyline.jpg"/>
      <ion-card-subtitle>Destination</ion-card-subtitle>
      <ion-card-title>Madison, WI</ion-card-title>
       </ion-card-header>
       
      <ion-card-content>
        Founded in 1829 on an isthmus between Lake Monona and Lake Mendota, Madison was named the capital of the Wisconsin Territory in 1836.
      </ion-card-content>
      </ion-card>

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
  IonCard, 
  IonCardHeader,
  IonCardSubtitle,
  IonCardTitle, 
  IonCardContent 
  } from '@ionic/vue';

export default  {
  name: 'Tab2',
  components: {
    IonHeader, 
    IonToolbar, 
    IonTitle, 
    IonContent, 
    IonPage,
    IonCard, 
  IonCardHeader,
  IonCardSubtitle,
  IonCardTitle, 
  IonCardContent
  }
}
</script>