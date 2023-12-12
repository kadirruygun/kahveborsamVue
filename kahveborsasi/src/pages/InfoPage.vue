<template>
    <div>
        <Navbar/>
        <NavbarBottom  class="q-mb-lg"/>
        <InfoComponent/>
        <FooterComponent/>
    </div>
</template>

<script lang="ts">

import Navbar from "../components/NavbarComponent.vue";
import NavbarBottom from "../components/NavbarBottom.vue";
import InfoComponent from "../components/InfoComponent.vue"

import { defineComponent } from 'vue';
import FooterComponent from "@/components/FooterComponent.vue";

export default defineComponent({


components:{ Navbar, NavbarBottom, InfoComponent, FooterComponent }
})
</script>