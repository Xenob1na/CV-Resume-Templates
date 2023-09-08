<!-- eslint-disable vue/no-unused-vars -->
<!-- eslint-disable vue/require-v-for-key -->
<template>
    <div class="container">
        <article class="social-tag">@johncarter</article>
        <img :src="socials.img" alt="" v-for="(socials, index) in social" class="social-img">
    </div>
</template>

<script setup>
import { ref } from 'vue';

const social = ref([
    {
        img: '/img/Facebook.svg'
    },
    {
        img: '/img/Linkedin.svg'
    },
    {
        img: '/img/Twitter.svg'
    },
    {
        img: '/img/Youtube.svg'
    },
    {
        img: '/img/Instagram.svg'
    },
    {
        img: '/img/Github.svg'
    },
])
</script>

<style lang="scss" scoped>
.container {
    padding-top: 180px;
    padding-bottom: 20px;

    .social-tag {
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: 9px;
        text-transform: lowercase;
        color: #fff;
        margin-bottom: 14px;
    }

    .social-img {
        margin: 10px;
    }
}
</style>