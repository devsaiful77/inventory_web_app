<template lang="">
    <div>
        <!-- main part -->
        <v-app id="inspire">
            <Sidebar />
            <v-main class="home-page">
                <router-view></router-view>
            </v-main>
        </v-app>
        <!-- main part -->
    </div>
</template>
<script>
import Sidebar from './Sidebar.vue'
export default {
    name: "App",
    components: {
        Sidebar,
    },
};
</script>
<style lang=""></style>
