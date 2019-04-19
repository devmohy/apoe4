<template>
    <div class="container-fluid px-0">
        <google-map />
    </div>
</template>

<style scoped>
    .vue-map-container{
        z-index:-1;
    }
</style>

<script>
import GoogleMap from "@/components/contact/GoogleMap";

export default {
    components: {
        GoogleMap
    },
    data() {
        return {
            
        }
    },
}
</script>
