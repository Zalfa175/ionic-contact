<template>
  <ion-page>
        
    <ion-header>
        <ion-toolbar color="tertiary">
            <ion-title>LATIHAN</ion-title>
        </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Latihan yehe</ion-title>
        </ion-toolbar>
      </ion-header>

      <ion-list>
        <ion-item @click="" class="ion-activable ripple-parent">
          <ion-ripple-effect></ion-ripple-effect>
          <ion-label>
            <p>State</p>
            <h2>State Management2</h2>
          </ion-label>
        </ion-item>
        
        <ion-item @click="" class="ion-activable ripple-parent">
          <ion-ripple-effect></ion-ripple-effect>
          <ion-label>
            <p>Iterator => v-for</p>
            <h2></h2>
          </ion-label>
        </ion-item>
        
        <ion-item @click="" class="ion-activable ripple-parent">
          <ion-ripple-effect></ion-ripple-effect>
          <ion-label>
            <p>If Statement - v-if</p>
            <h2></h2>
          </ion-label>
        </ion-item>
        
        <ion-item @click="" class="ion-activable ripple-parent">
          <ion-ripple-effect></ion-ripple-effect>
          <ion-label>
            <p>Model - Two Binding - v-if</p>
            <h2></h2>
          </ion-label>
        </ion-item>
        
        <ion-item @click="" class="ion-activable ripple-parent">
          <ion-ripple-effect></ion-ripple-effect>
          <ion-label>
            <p>Event</p>
            <h2></h2>
          </ion-label>
        </ion-item>
        
        <ion-item @click="" class="ion-activable ripple-parent">
          <ion-ripple-effect></ion-ripple-effect>
          <ion-label>
            <p>Lifecycle</p>
            <h2></h2>
          </ion-label>
        </ion-item>

      </ion-list>
    </ion-content>
</ion-page>
</template>

<script setup lang="ts">
import { useRouter } from "vue-router";

const router = useRouter()

</script>

<style></style>
