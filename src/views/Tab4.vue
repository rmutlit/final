<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Grid</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Grid</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ion-grid>
        <ion-row>
          <ion-col>
            <div>1 of 2</div>
          </ion-col>
          <ion-col>
            <div>2 of 2</div>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <div>1 of 3</div>
          </ion-col>
          <ion-col>
            <div>2 of 3</div>
          </ion-col>
          <ion-col>
            <div>3 of 3</div>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col>
            <div>1 of 3</div>
          </ion-col>
          <ion-col col-6>
            <div>2 of 3</div>
          </ion-col>
          <ion-col>
            <div>3 of 3</div>
          </ion-col>
        </ion-row>
        <ion-row>
          <ion-col col-6>
            <div>1 of 3</div>
          </ion-col>
          <ion-col>
            <div>2 of 3</div>
          </ion-col>
          <ion-col>
            <div>3 of 3</div>
          </ion-col>
        </ion-row>
      </ion-grid>

       </ion-content>
  </ion-page>
</template>

<style>
    :root {
      --ion-safe-area-top: 20px;
      --ion-safe-area-bottom: 22px;
    }

    ion-col > div {
      background-color: #c0bfbf0a;
      padding: 10px;
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
  name: 'Tab4',
  components: { 
    IonHeader, 
    IonToolbar,
     IonTitle,
      IonContent, 
      IonPage
       }
}
</script>
