<template>
    <div>
        <Navbar/>
        <NavbarBottom/>
        <Product/>
        <FooterComponent />
    </div>
</template>

<script lang="ts">

import Navbar from "../components/NavbarComponent.vue";
import NavbarBottom from "../components/NavbarBottom.vue";

import Product from "../components/ProductComponent.vue"

import { defineComponent } from 'vue';
import FooterComponent from "@/components/FooterComponent.vue";

export default defineComponent({


components:{ Product, Navbar, NavbarBottom, FooterComponent }
})
</script>