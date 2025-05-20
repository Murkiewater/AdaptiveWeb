<script setup>
import VHeader from './components/VHeader.vue';
import VFooter from './components/VFooter.vue';
import VPromo from './components/VPromo.vue';
import VFomina from './components/VFomina.vue';
import VHistory from './components/VHistory.vue';
import VOpportunities from './components/VOpportunities.vue';
import VHowItsWork from './components/VHowItsWork.vue';
import VDistantLess from './components/VDistantLess.vue';
</script>

<template>
    <v-header />
    <main>
        <v-promo />
        <v-fomina />
        <v-history />
        <v-opportunities />
        <v-howItsWork />
        <v-distantLess />
    </main>
    <v-footer />

</template>

<style scoped></style>
