<template >
    <Nav/>
    <BottomHomeVue/>
    </template>

<script>
import { Link } from "@inertiajs/inertia-vue3";
import BottomHomeVue from '../Components/containerForVue/BottomHome.vue';
import Nav from '../Components/containerForVue/Nav.vue';


export default {
components: {
    BottomHomeVue,
    Nav,
    Link,
},

    
}
</script>

<style >
    
</style>