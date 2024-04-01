<template> 
    <ion-page>
        <ion-header>
            <ion-toolbar color="tertiary">
                <ion-buttons slot="start">
                    <ion-button @click="back">
                        <ion-icon slot="icon-only" :icon="arrowBackOutline"></ion-icon>
                    </ion-button>
                </ion-buttons>
                <ion-title>Input Contact</ion-title>
            </ion-toolbar>
        </ion-header>

        <ion-content>
            
            <ion-card>
                <ion-card-header>
                    <ion-title>Input Data Contact</ion-title>
                </ion-card-header>

                <ion-card-content>
                    <ion-list>
                        
                        <ion-item>
                            <ion-input label="Nama" v-model="name" label-placement="floating" placeholder="Masukkan Nama"></ion-input>
                        </ion-item>
                        
                        <ion-item>
                            <ion-input label="Email" label-placement="floating" placeholder="Masukkan Email"></ion-input>
                        </ion-item>
                        
                        <ion-item>
                            <ion-input label="Telp" label-placement="floating" placeholder="Masukkan Telephone"></ion-input>
                        </ion-item>

                        <ion-list>
                            <ion-list-header>Jenis Kelamin</ion-list-header>

                            <ion-radio-group>
                                <ion-item>
                                    <ion-radio value="1" justify="end">Laki-laki</ion-radio>
                                </ion-item>
                            </ion-radio-group>

                            <ion-radio-group>
                                <ion-item>
                                    <ion-radio value="2" justify="end">Perempuan</ion-radio>
                                </ion-item>
                            </ion-radio-group>
                        </ion-list>

                        <ion-item>
                            <ion-select label="Tipe" placeholder="Tipe Kontak">
                                <ion-select-option value="0">Biasa</ion-select-option>
                                <ion-select-option value="1">Favorite</ion-select-option>
                            </ion-select>
                        </ion-item>

                        <ion-item>
                            <ion-textarea label="Alamat" label-placement="floating" placeholder="Masukkan Alamat"></ion-textarea>
                        </ion-item>

                        <ion-button expand="block" color="tertiary">Simpan</ion-button>
                    </ion-list>
                </ion-card-content>
            </ion-card>
        </ion-content>
    </ion-page>
</template>

<script setup>
import { useRouter } from "vue-router";
import { arrowBackOutline } from "ionicons/icons";

const router = useRouter()

const back = () => {
    router.back()
}
</script>