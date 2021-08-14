<template>
  <div id="container">
    <ion-list>
      <ion-list-header>Badges</ion-list-header>
      <ion-item>
        <ion-label>Followers</ion-label>
        <ion-badge slot="end">22k</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Likes</ion-label>
        <ion-badge color="secondary" slot="end">118k</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Stars</ion-label>
        <ion-badge color="tertiary" slot="end">34k</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Completed</ion-label>
        <ion-badge color="success" slot="end">80</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Warnings</ion-label>
        <ion-badge>dfdfsdfsasdfsdfd</ion-badge>
        <ion-badge>dfdfsdfsasdfsdfd</ion-badge>
        
        <ion-badge color="warning" slot="end">70</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Notifications</ion-label>
        <ion-badge color="danger" slot="end">1000</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Unread</ion-label>
        <ion-badge color="light" slot="end">24</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Drafts</ion-label>
        <ion-badge color="medium" slot="end">14</ion-badge>
      </ion-item>
      <ion-item>
        <ion-label>Deleted</ion-label>
        <ion-badge color="dark" slot="end">4</ion-badge>
      </ion-item>
    </ion-list>
  </div>
</template>

<script lang="ts">
import { IonBadge, IonItem, IonLabel, IonList, IonListHeader } from '@ionic/vue';
export default {
  name: 'BadgeContainer',
  components: {IonBadge, IonItem, IonLabel, IonList, IonListHeader },
  props: {
    name: String
  }
}
</script>

<style scoped>
#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #8c8c8c;
  margin: 0;
}

#container a {
  text-decoration: none;
}

#container .sss {
  background: none;
  color: #000
}
</style>