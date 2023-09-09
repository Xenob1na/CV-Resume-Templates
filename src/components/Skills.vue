<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <div class="container-Skills">
        <p class="Skills-line"></p>
        <h3 class="Skills-h3">Skills</h3>
        <div class="Skills-wrapper">
            <div class="Skills-box" v-for="(icon, index) in icons" :key="index">
                <img :src="icon.img" alt="icon" class="Skills-icon">
                <p class="Skills-p">{{ icon.name }}</p>
            </div>
        </div>
    </div>
</template>

<script setup>
import { ref } from 'vue';

const icons = ref([
    {
        img: '/img/html.svg',
        name: 'HTML & CSS'
    },
    {
        img: '/img/js.svg',
        name: 'Javascript'
    },
    {
        img: '/img/react.svg',
        name: 'React JS'
    },
    {
        img: '/img/webflow.svg',
        name: 'Webflow'
    }
])
</script>

<style lang="scss" scoped>
.container-Skills {
    max-width: 400px;

    .Skills-line {
        background-color: #fff;
        width: 58px;
        height: 3px;
        margin: 0;
        margin-top: 30px;
    }

    .Skills-h3 {
        margin: 0;
        margin-top: 13px;
        font-size: 18px;
        font-style: normal;
        font-weight: 700;
        line-height: 130%;
        color: #fff;
    }

    .Skills-wrapper {
        display: flex;
        gap: 15px;

        .Skills-box {
            margin-top: 24px;

            .Skills-icon {
                width: 40px;
            }

            .Skills-p {
                font-size: 16px;
                font-style: normal;
                font-weight: 700;
                line-height: 130%;
                color: #fff;
            }
        }
    }
}</style>