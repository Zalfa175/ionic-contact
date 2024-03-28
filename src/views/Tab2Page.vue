<template>
  <ion-page>
        
    <ion-header>
        <ion-toolbar color="tertiary">
            <ion-title>CONTACT'S FAVORITE</ion-title>
        </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
        <ion-list>
            <ion-list-header>
                <ion-label>Daftar Kontak</ion-label>
            </ion-list-header>

            <ion-item-sliding>
              <ion-item>
                <ion-label>
                  <h2>Nama</h2>
                  <p>nomor</p>
                  <p>email</p>
                </ion-label>
              </ion-item>
          
              <ion-item-options>
                <ion-item-option>
                  <ion-icon slot="start" :icon="heart"></ion-icon>
                  Unvaf
                </ion-item-option>
                <ion-item-option color="danger">
                  <ion-icon slot="start" :icon="trash"></ion-icon>
                </ion-item-option>
              </ion-item-options>
            </ion-item-sliding>
        </ion-list>

    </ion-content>
</ion-page>
</template>

<script setup lang="ts">
import { trash, heart } from 'ionicons/icons';

</script>

<style></style>