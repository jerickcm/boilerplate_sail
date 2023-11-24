<script setup>
import { Link } from "@inertiajs/vue3";
import Footer from "../Components/Footer/footer.vue";
</script>

<template>
    <div class="min-h-screen bg-gray-100">
        <div>
            <!-- <div id="holder"> -->
                <!-- <div id="body"> -->
                    <main>
                        
                    </main>
                    <!-- <div style="min-height: 460px"></div> -->
                <!-- </div> -->
                <slot />
                <Footer />
            <!-- </div> -->
        </div>
    </div>
</template>

<style scoped>
/* .second-nav {
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    opacity: 0.9;
}

#holder {
    min-height: 100%;
    position: relative;
}

#body {
    padding-bottom: 100px;
}

footer {
    height: 100px;
    width: 100%;
    position: absolute;
    left: 0;
    bottom: 0;
} */
</style>
