<template>
    <ion-page>
        <ion-header>
            <ion-toolbar color="primary">
                <ion-title>Under Construction Page</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content :fullscreen="true">
            <ion-header collapse="condense">
                <ion-toolbar>
                    <ion-title size="large">Under Construction Page</ion-title>
                </ion-toolbar>
            </ion-header>

            <div class="image-container">
                <!-- <img src="/images/under-construction.png" alt="under construction" srcset=""> -->
                <!-- <img src="/images/under-construction-2.png" alt="under-construction" srcset=""> -->
                <img src="/images/under-construction-3.png" alt="under-construction" srcset="">
            </div>

        </ion-content>
    </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>

<style scoped lang="scss">
.image-container {
    display: flex;
    justify-content: center;
    /* Pusatkan secara horizontal */
    align-items: center;
    /* Pusatkan secara vertical */
    height: 100vh;
    /* Ambil tinggi penuh layar */

    img {
        max-width: 100%;
        /* Responsif */
        height: auto;
        /* Pertahankan rasio aspek */
    }
}
</style>