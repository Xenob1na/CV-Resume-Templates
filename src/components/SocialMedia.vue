<!-- eslint-disable vue/no-unused-vars -->
<!-- eslint-disable vue/require-v-for-key -->
<template>
    <div class="container">
        <article class="social-tag">@johncarter</article>
        <a :href="socials.link" v-for="(socials, index) in social">
            <img :src="socials.img" alt="" class="social-img">
        </a>
    </div>
</template>

<script setup>
import { ref } from 'vue';

const social = ref([
    {
        img: '/img/Facebook.svg',
        link: 'https://m.facebook.com/'
    },
    {
        img: '/img/Linkedin.svg',
        link: 'https://ru.linkedin.com/'
    },
    {
        img: '/img/Twitter.svg',
        link: 'https://twitter.com/'
    },
    {
        img: '/img/Youtube.svg',
        link: 'https://www.youtube.com/'
    },
    {
        img: '/img/Instagram.svg',
        link: 'http://instagram.com/'
    },
    {
        img: '/img/Github.svg',
        link: 'https://github.com/'
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
        cursor: pointer;
    }
}
</style>