<template>
    <div class="container-fluid" id="privacy" :style="{ backgroundImage: 'url(' + require('@/assets/img/r29.png') + ')' }">
        <div class="container">
            <h1 class="font-weight-bold text-white">Privacy</h1>
            <p class="text-white">This is a sample content privacy us. This is a sample content privacy us</p>
        </div>
    </div>
</template>

<style scoped>

    #privacy {
        background-repeat: no-repeat;
        background-position: right;
    }

    #privacy .container {
        height: 300px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: left;
    }

</style>

<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>
