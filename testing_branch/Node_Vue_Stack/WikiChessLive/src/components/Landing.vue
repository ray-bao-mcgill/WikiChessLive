<script setup>
import { ref } from 'vue'
import Title from './Title.vue'
</script>

<template>
    <div class="main-wrapper">
        <div id="title">
            <Title></Title>
        </div>
    </div>
</template>
<style scoped>
    #title{
        position: relative;
        top: 20%;
    }
    .main-wrapper{
        display:flex;
        justify-content: center;
        position: absolute;
        width:100vw;
        height: 100vh;
        margin: 0;
        padding: 0;
        background: #457b9d;
        font: Panton;
    }
</style>